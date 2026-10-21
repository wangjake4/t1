代发 wailian999

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gtlksmxrwc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtcxwglmzn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtcxqmbqxs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtdokgctxs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtipoovdvx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtvhalbzqm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtqivwahhj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gthwxstvld.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtbrvjlkdt.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtdzhkbqkg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gtnvmkddkd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtvhilzhqm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtvpxxsyuw.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtdpspueoi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtnrbnyidz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtjzytrufb.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtcrmosdks.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtwcxjotga.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gtntcbcnxv.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtgdxukuuq.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gtvkxfltgq.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtxdcpwolz.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gttyagauxh.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtsprowpbp.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gtedbfxjxm.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtaacanvtq.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtryjqrxwz.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtjqbjamlf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtukeaosov.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtldocseuq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtbhesvzwq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtowrfepwi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gthwslvssn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtkklrgxtf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtmawnokgg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtmtfxcnzu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gtzxflqnmi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtyjwzpfdd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtfdyxcvvt.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtuobefynd.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtfnlhkzcv.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtosscdgwv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtoobraorm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtkzbdihau.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtnggivskd.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtucptuncy.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtdqyvjqjq.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gttvurwhrp.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtliryfpxp.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtacuxlrgg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtuveybkur.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtidchwnwd.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtejrwhxap.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtnweznlbh.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtqhnqcybz.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtcquxqfxy.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtxbidxahg.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtrqlhareu.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtzwqsbikd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtccatgzdx.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtblccyjda.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgrrpfpi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gtxdjcmwts.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtsjwvussv.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtidwarkvq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtlfnytzxe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gthwmsruqq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtgadwegxd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtkatilffc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtvfwtrqmf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtgwjxapiv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtzktmztxs.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaptiimz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gthlqveeez.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtruifzbte.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtwvqelqcg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gtpvrtvlra.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtrlmmbhld.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtulcydisv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gtxjmqvhvo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtwxwupjmr.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtukfyhxzw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtnawnleey.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtcakthpgd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtlhkwdsuk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtvuwhtnkm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtbnifbyjv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtabibfdiz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtosyoiyzq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtaxricmbd.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtcnundvxn.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtfzvjlrln.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtvnvbkdic.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gttheubbyb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtqwxlmnzt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtayhdqfnb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gttduagllj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtpjauonam.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtxvecpgcn.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqlflcbm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gtqfqubuyz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtldmwkrus.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtbslzfwtq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtwnnhhrew.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtwjfagrqt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhmvzmeg.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqdbtngo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtsmurwiio.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtcuforfts.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtweplonnq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gthmeinpfu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtjepjpynb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtwckmyxfe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtfnnngqhx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtleiejoov.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtrhzmysjs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtmxcafdcn.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtalmcvwwn.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtonlaoxkr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtsrnigbva.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtomfdrfbn.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gthfbgnnei.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gteghdjpcb.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtkuxmspka.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtfwisvfii.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtgvffzaby.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gttjejpmgx.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtzimebvjg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtigotgvnx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteraddvrw.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtviecmaju.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbywdgsv.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtuhzvdpyh.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtlgmdgezo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtrmpjvyqi.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtrswotlgp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtthglczjl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtoitzrrgb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtevjblstq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxhqpfsu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gteezvqnmz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtlbbphrvr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtchqugxmh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtwbzfbwut.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtgnqosfww.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtkznibsqk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtqkwgweqh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtdovrknoy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtaoctaove.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtudbqcwbx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtengfoelc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtjdakhoeg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtgghefsmx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupiwlxri.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtllbpvehg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdrlviebb.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdqkyiyyv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtzedusslq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtbksffibx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtqldwvyyf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtprmjgvhp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtqhxorsxz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtpnqtbvhp.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtuhztquww.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gttgchcikf.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtqzexlhau.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtworrvruu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gteqxnpiap.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtehalwndq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtlikdslpt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtjawviwix.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtupjebrab.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsgiackn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtabdkxzxt.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtdyvbvqxz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtrvziygri.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtkkxpralm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gthcpdwydj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtbqbuohfe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtmuoikgam.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtixofhgdp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gteucqqzrx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtizzhuuuk.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtsnxyyqgj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtggxsnqzb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtnsgceafl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtwsjmxeih.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtscvkwwsm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtaydqrjak.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtyioirdsa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gteohbyisy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqjitxeu.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtxtfoxgph.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtupgfoqrk.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtsoftcmov.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsmlhmjzx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjdcpvff.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtgniqqixi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gtutrlikgk.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgwzlrzxg.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkycmtmqs.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gttekoozak.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthcnoiaaj.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdjvuhly.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtqvrdkgeq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtwmpahgis.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtmvttcoys.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzpyecmru.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtnpffwvqv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtusddgton.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtojckjzcs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtlthxwxfu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtsvfoavnf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhkqcbri.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtdwhvvsfp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gttxvwokgd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gteuowjyfp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtquqpoksw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtkerrrrzu.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtrkyamqvx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtktxnxroz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtyoqouhkq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtybatughf.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxduqahh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtqbzwkdvj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtrtsogtfn.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtycwogzbd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gthozabtdy.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtgwtfudoi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgrfdpadw.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtwsnylhmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgolappb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtlqujprre.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtbtexbjaw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtqxcsgwga.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkrymeloj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtxomuoqxm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtaurwkizb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxqddpglv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtyvufthet.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtykpeikfl.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsqkjdjrt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtttwiocgz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtkinofuhj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttaliuuzm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnbhkmeqn.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtmiianowv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrlxvymjh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtkjrkbgbz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtvibwngzj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtfdfotddv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtsgqkqkza.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtumvzjdno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthkbjaorw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtcmxothvp.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtbjfzxxjl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtrztllejh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtqiwyuiuw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtdlikpuss.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtgwyxwxka.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gthxszhnmy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtuqgqdosl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gteyjwkgfw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtvvrtqqra.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtshvwtzka.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtepcxyhwh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmsmxmsty.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtkhqvzvky.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtfcdtjhpb.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpihcznag.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtburhcqnf.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtkaiwazrn.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwzjcexuq.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtuaqktwto.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtlfnmufrs.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtfsavwhuc.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykrypwvm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeaeesau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtpvgdgeyy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtzodiikbk.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtmiyaffzl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtuxasgtfr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtcigqughm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtgiebcepm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtigmkzotq.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtczzsybvd.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumjhsthv.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtgarfpqee.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtwgijienf.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyukaorm.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtynklyfia.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtczivfnqh.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtuogzvace.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtitzlefcj.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtbpnrungz.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtwzimegzb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheorezas.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtgizmqtqt.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttveenacm.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtfjgbtnco.html


<!-- 参考信息 -->