// Raymond Kuka Mosegi Solia
// 02/13/2025
// 


class Hand:
    """



    def _init_(self):
        self.cards = []


    def addCard(self, c):
        self.cards.append(c)


    def removeCards(self):
        self.cards.clear()


    def getHandValue(self):
        hand_value = 0
        has_ace = False

        for c in self.cards:
            hand_value += c.value
            if c.is_ace ==True:
                has_ace = True

        if hand_value > 21 and has_ace == True:
            for cd in self.cards:
                if hand_value > 21:
                    if cd.is_ace == True:
                        hand_value -= 10

          return hand_value


      def printHand(self):
          output = ""
          for c in self.cards:
              output += c.face + " "
          return output.strip() {

      }
