import requests

url_ddg = "https://api.duckduckgo.com"
resp = requests.get(url_ddg + "/?q=presidents+of+the+united+states&format=json")
rsp_data = resp.json()
# print(rsp_data)
related_topics = rsp_data["RelatedTopics"]
#print(topics)
all_texts = ""
for topic in related_topics:
    all_texts += topic["Text"]

#print(texts)


def test_Washington():
    assert 'Washington' in all_texts


#Covers John Adams (2nd President) and John Quincy Adams (6th)
def test_Adams():
    assert 'Adams' in all_texts


def test_Jefferson():
    assert 'Jefferson' in all_texts


def test_Madison():
    assert 'Madison' in all_texts


def test_Monroe():
    assert 'Monroe' in all_texts


def test_Jackson():
    assert 'Jackson' in all_texts


def test_Buren():
    assert 'Buren' in all_texts


# Tests William Henry Harrison (9th President) and Benjamin Harrison (23rd)
def test_Harrison():
    assert 'Harrison' in all_texts


def test_Tyler():
    assert 'Tyler' in all_texts


def test_Polk():
    assert 'Polk' in all_texts


def test_Taylor():
    assert 'Taylor' in all_texts


def test_Fillmore():
    assert 'Fillmore' in all_texts


def test_Pierce():
    assert 'Pierce' in all_texts


def test_Buchanan():
    assert 'Buchanan' in all_texts


def test_Lincoln():
    assert 'Lincoln' in all_texts


#Covers Andrew Johnson (17th President) and Lyndon B. Johnson (36th)
def test_Johnson():
    assert 'Johnson' in all_texts


def test_Grant():
    assert 'Grant' in all_texts


def test_Hayes():
    assert 'Hayes' in all_texts


def test_Garfield():
    assert 'Garfield' in all_texts


def test_Arthur():
    assert 'Arthur' in all_texts


def test_Cleveland():
    assert 'Cleveland' in all_texts


def test_McKinley():
    assert 'McKinley' in all_texts


#Covers Theodore Roosevelt (26th President) and Franklin D. Roosevelt (32nd)
def test_Roosevelt():
    assert 'Roosevelt' in all_texts


def test_Taft():
    assert 'Taft' in all_texts


def test_Wilson():
    assert 'Wilson' in all_texts


def test_Harding():
    assert 'Harding' in all_texts


def test_Coolidge():
    assert 'Coolidge' in all_texts


def test_Hoover():
    assert 'Hoover' in all_texts


def test_Truman():
    assert 'Truman' in all_texts


def test_Eisenhower():
    assert 'Eisenhower' in all_texts


def test_Kennedy():
    assert 'Kennedy' in all_texts


def test_Nixon():
    assert 'Nixon' in all_texts


def test_Ford():
    assert 'Ford' in all_texts


def test_Carter():
    assert 'Carter' in all_texts


def test_Reagan():
    assert 'Reagan' in all_texts


#Covers George H.W. Bush (41st President) and George W. Bush (43rd)
def test_Bush():
    assert 'Bush' in all_texts


def test_Clinton():
    assert 'Clinton' in all_texts


def test_Obama():
    assert 'Obama' in all_texts


def test_Trump():
    assert 'Trump' in all_texts


def test_Biden():
    assert 'Biden' in all_texts
