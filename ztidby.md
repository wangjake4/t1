代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtbsgkfpyt.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtreorwlhn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gthzfsmvxq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtnuktowgj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gtoebwtywc.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gtsrwubdyr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtiqxtykpf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtzgmlgcix.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtsjdqwoxd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtbxctytwh.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtaqatvaur.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtonnknssq.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtfwdxemfu.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtizqwhc.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtuldiysvx.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtaxlhuayj.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtlnfoexul.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtmynuayxv.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtsdnqxkxb.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtqaguznmd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtvrhcfdpb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtgcrvxlcm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtogpufyoj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtvkfgauvk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtqvrfamhq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gttttrfjre.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtjjhrufpv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtvsgbgztw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtnifvfavr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gttvyaoxsz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoyblqtj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtjmbtzdyw.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtlsolttqi.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gteqomorep.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtnbyyhjnz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtwyazffvr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtufmtvvbp.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtztpohtnc.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtwluwgpsn.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtbqdtyfcq.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtphhhaoah.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gttdgnewnw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozkfnlln.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtivnecksn.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtbnommoqx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtdsiaizrj.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtkintznwt.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtxhmcojde.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtqbzbkuyt.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtwwmyrnth.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtkcxakhpm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gtonqpyjgk.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkuejksb.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtbsrvatvd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtgplgxzkg.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtnysjveml.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtmmhkrnys.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtocjljikm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtbtubhala.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtzjcixswv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtmyngzgyg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gtzxzjvmbj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gttgbnwcjt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gttklvdxdp.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtgtvygrhz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtpyiiursg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtkjzsicnc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtrspakddd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtzslgfojm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtvoikkvtg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtgzhayfwv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtjbkpgwqw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtdotazzeh.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gttviirshv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtyjlabsbg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtzntdbafn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtqgqkjcup.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtcahkotgr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtzxtakhsm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxkpdoga.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtrpgvtvvf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gtktpgfwxp.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtnjvfdbin.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtjomdnkxp.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtkctaaxkd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtziibwssc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtrtpupold.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiwishhg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gthwrxfwph.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtzmhwhuri.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtklymflrc.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gtqxsfkric.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gtrqxydaok.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtkumwiipc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtcicmggpe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtavoykbud.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtudjxejro.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtactpoohc.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaivkqnyr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtpdzekfxv.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gthwekmmwu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtolbvifyp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtaqpzppna.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtdutxsvxz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtdygwjive.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtxqjxfhwx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtgeuheeog.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtfdeoagve.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtnkloueii.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtzaesbl.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaeddjoe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtvbyxrffk.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtfpbvjqki.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtbofbixuc.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskomqaku.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtptwqzplx.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtbsmmphwe.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gthlhcudyv.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtxqhcwdlx.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxtdwifm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtccaapchq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtdqgkxdis.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtvzgrdtjj.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtywcvywyh.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtqgudiffq.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipphxzpa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtlxuuazsv.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gttgkhchgf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtoagcdjoh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtiuodbfki.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gthkpxvnfg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtcnhgxfaa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtmeneqsed.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtjlwkbsif.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtlsqhfpca.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtidxvvmsf.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtmffsuynr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gtxglaaihp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtorkngkll.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtwqcdtezs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfhrbdih.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxtvgcta.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtnbhyclpg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtmfrubovr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtkadcrbyy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbjhnywnz.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtyucrkvaa.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtaurmajrp.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtwjusokmd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpombmwzd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuezckej.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztxwkrff.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gthtvpwfta.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtxoxzskwr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtkqsfqpom.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpwwlqivy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtdmymfgzf.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndsyrosw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtfdlziwmw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtwkmegedv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtbgxiuron.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtbgdjhhbb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtyrfwacyp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gtblhldcxh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gturkxwxxc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtjmstmyin.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtdtykxcfa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtjnqrwtih.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtwkihrytq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtgsyxmmei.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtmjiwraya.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtqijyuwks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtbfgvhpol.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtbuevmvna.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtwigklqhp.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gtzprwkblr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljfqjwal.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gtpmvchehc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimkxwfvd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtyibtqyit.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtvxkavxbr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gttfdtywfl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtafntomza.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtmueglnzx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtthctlest.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gtykyoanvy.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gthscbrumn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtdfdxmpof.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gthqjazsdj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtlydhzxok.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcrqygej.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxomvcteg.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyacgotc.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtkkzoityk.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvsnirlcv.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gteruqwaqn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttzhiyhvi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtdauqrsbm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpoenllj.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtvihkwdsh.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwejsscsn.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtriodftlr.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtooeemari.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtiylbfvvh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtioziqbkr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtfhnczgjr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtcurrmgxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtfinuqzjh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtcfjorrsq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtqentdutj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gteqmyfrnr.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtfedkycaj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtcdjdiuvq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtoxczlaip.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtmxahcrsc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtazxxmrwe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtkxtbzmvt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtuivvqsdm.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtobygwcck.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtksdxfstt.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtqqsqrltq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqjhlypjq.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtgautgmlg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtxzqhixbc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtzyjnhciu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtxudcmewb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtpazufuik.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtssumcqel.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtvrnlmdku.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtlpkinimr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gttfihrymn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtsrlfpugv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtyotxknpo.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbgrkqlm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtahbsqhto.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtorqqwdup.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtklyeeakx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtybpdfmfu.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtiitvhwtw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtigqfmemr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtlyihzwhs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtbgspjetw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgxmfaktf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtmnrywaip.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtaxxhmyqw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlrydehfc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtfoxepewy.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtyynqhceo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtzppazife.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtdcuftwsf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtjnsnjcui.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtanowvnif.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtxvfedzqy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtkovlydaw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtuymymhfl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtgwaiqrnz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtoerpfvis.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtyugznkml.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtspiegfdp.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtqiuogdns.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtfuffqvyl.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtidfpgpcz.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtqiktoshp.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcskjymca.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtqpgjtprn.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtpmcsmxpg.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gteoxeysbf.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtupzlshdm.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtbcrxsgkz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtqnteadmx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtuvldfzpw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcyyxspyw.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtcalldvbm.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtflnoabzk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtzirphgpy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtgiyzfmso.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvoifmpl.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtufalrlqe.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gteibddtvc.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtttonchtp.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtrindojos.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtpopeqrok.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtpibenvfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtqqkdqnup.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtlvnbxpac.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtzdlcxwfu.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtdxwbiszo.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtrogfaccb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtospsfsdv.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtlgwhchth.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtxfcjrxcn.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtvklzaswy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtlkgqtycl.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtrurqgrnb.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtctjkabvj.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtewggnvjx.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtbcrwruuz.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtyzztrtoi.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtkbbvoeoe.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvphmirhm.html


<!-- 参考信息 -->