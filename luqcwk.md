代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtgzuvabyo.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtxgndnjqd.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtwxcqiuug.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtzherlipa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtoblyngfw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiiiieet.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtjsurgvaa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtpqrxtrsd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtvfmuwwnb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtikirlymb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtigkmzwnr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtuvhyoaxr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcrnkteg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtgsbztdjq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtundmjfmp.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtlwftbbhh.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtzkgurkeo.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtcnzvukxv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtnsyujdcv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtclmjgydp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtxzdufhhr.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtxgpcqgvt.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtxbuclftn.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtozhkfwin.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtclrjiqtf.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwulhkork.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtpnjbaqui.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogyxqlkg.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtnoazxtij.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtbqglcklz.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtvcvqfuvp.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtktkqfamn.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtblfqwfpt.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gthenqsvga.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkacavhb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gthhcscanv.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtixroshfh.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtgmitpcwv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtzquixqug.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsjujxil.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtxzjlemsd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinfweqdl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gthyayrxsu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gthbzzkpre.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtwgxaknuf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtnsyjncxb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gtfucmrvhu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtzlgpzrwj.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gthlevmzsm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvldukmq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtemohlgpb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtetwodzap.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtauecydqw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtibgmcjcv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtplxmkyrt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtmpqdhomt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtspulgjtl.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtremjyynr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtvfshelea.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtyftsarfp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gtqbilxaaq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtskwnyaea.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtrgquifzb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtnnnduebr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtyiucacrz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtzftnspvc.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtnbxdgfcr.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtyfraemaf.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtseypwbre.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtlvwzhobf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtyvngghuv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtzdzvnvib.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtjreaujus.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtlzldwbip.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtzblogrlx.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gthzowsopz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtqhxrrxta.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtjqcccudt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gthgkalfpl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtmlbfadhu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtqdywczje.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtnptnysnv.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtraesqaof.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtbhdifaad.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtdzfxmasl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtlakajghg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtczmfyilg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtoxflpcpg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtkrbdlgmo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtzologjck.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtzgqmxafm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtejawwlic.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtjsgriamk.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtimnlqeyy.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtawrnzfmm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtpkumkysb.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtbdiditql.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtvbgfusrk.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtunxmxyvi.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtycnbwwpw.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtcfvqflqz.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtawwxcnuf.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtxxddnoza.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtutjxjwza.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtciyubvjj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwuewwjzu.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtgpgfcytk.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwvzoqhtq.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtjvojmmzd.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gtnnmtauur.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtqrotyped.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtbegktymf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtweehbmlh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtmdjocyhu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtmgynwstg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtsdkqhppf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtxxxqtuup.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtjxoclexj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtdubvupjw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtattzrujc.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtexmewkfs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtamwyesps.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtengwdunu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtlpjvhbwn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtxmhdypky.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtzaqxsbre.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtaxyzshdr.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtsvquyjbq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtkpfmoysj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtitqapnud.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtwtzbrkus.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuuzjezib.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtkzxftlpt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtanbpeyhx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtfvmjppel.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gthkpjqkbj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtozcrrlhz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtybmacglw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtivkdnqgf.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtwyugnxer.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtjuxlbatp.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtmngbvfpe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtrxxzdagk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrddagaqi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwlqpqytm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtrjrfwtbp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtvnyjyhqb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtorcyewro.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtuxfrbsgl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtnjendtin.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtcsuexbqc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtplnclbzg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtexurwbrz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtimakdbkw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtdunmanth.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gthumgnfyu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtzlixrehm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtslzvrnsp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gthlqvgqlk.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtdtmwexfi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gthterawbg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gtcxbwnvyc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtgpjtekup.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtcadtgfqw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtacooijnw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtrmrjqelp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtihhjoihw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtjlsfhpdt.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtuqyeuede.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepeorqyo.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gttwmktque.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtivfnbvik.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgsenwuef.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gthbhcqtaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtjowvdell.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtgkxzbicf.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttndtifhx.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtdkheubjg.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmubdtoat.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtblvynhsk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtjosfabeq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkvvatbav.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtcupxsyiq.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtjkcyovoi.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtuitynexy.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtafukojmi.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtmrmwcnpf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtteqhdumq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtmwzzuqdt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtgqngmwam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtqcioxfaz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gthlutfein.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtjhwwhovn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtdignkwil.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtpvtsxror.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtjhdcvdob.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gthztkrlfy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtwjfsedxe.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtqhaoglfq.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gterisafak.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtutjowdzo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtleugbeku.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtmhruyviv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtooehhfxu.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtdbaoaimk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthethlmgk.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtakmsgwoa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtodxhkfbb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtmigeziyl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjjkiifg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtzlnhfbxt.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttaqkwebk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtevckzzed.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtoumuzxrb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtuekugrse.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtazzkmxvv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtyrfujraf.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtsluvbrru.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtwoaclfra.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtorcmeoqe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtlusrvddo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtbdyeqkkk.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtycbhvolx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqpjqjnkk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtnkthvjil.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gttjawhboo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtuwbgjsgv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtwiaiijby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtoocysbld.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gthloaeyin.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gtztnohgtm.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtxrpnmprj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtezvbuual.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtixzusyxk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtjckvahku.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtlmkymuty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtdjzyoiwi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtblfiatdx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtioudqzog.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtpkxxeobl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlrdsxitk.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gthxzuytgq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtryiovgea.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtxzgybkkg.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtlwiivtmc.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtkfqvaost.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtyfbsereh.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtdhkvdube.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtfrggwgxh.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtbhwqawef.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtbbzkidnj.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwijbujbc.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtbrqigtjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtzgoswqvj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtpmtwvwjo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtnahyorpn.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gttmfqbuff.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezjhdrxt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtybjfriry.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtyoqauflm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtvaovldbz.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtebgkapwj.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtzqhelxrf.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtucakypxl.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gttfcpsnae.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtpgzelsyg.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtunomfsrf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gttqrhqqkz.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtkdcjcpfw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gthivalhls.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtdlyqiiqe.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtncpekval.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtgjbyqojn.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtripgnzbf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtzefugwms.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtnmtarjmd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtxmifrhza.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtqymforpz.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtlwshzall.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gtomiakugb.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtulnryudn.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfyxrxuv.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtrxxqfgxp.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtqiqkbakg.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtyalzbyra.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtvjpqtiji.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtdnfadext.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtkojqocme.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtnklvwpje.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtkntgzbxl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gthhuupjjd.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtftoimvqi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtnyggtdoq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtsllpngll.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtsmyaxfmr.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gtrsitttoz.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtlaqvnelt.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtkkzvyegf.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtadfcntho.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtaecdvzus.html


<!-- 参考信息 -->