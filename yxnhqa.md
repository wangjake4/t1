代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gt2rknkfiol.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2occgqejl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpdurodo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2wyzynqep.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2jjgexybq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gt2uskmjkbi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2qwfeizbd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2odxyvhgq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gt2dlflinah.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2nbwepidv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gt2cfonqdhu.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2fnghnyfw.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2itmberht.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2viearxwl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2fqiuwrcm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2ubxszrbn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2mftrznhw.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2vcslneot.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2ulftmixz.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2fortoekk.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2wanagoqm.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2nizqnpqc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gt2jddqwpmw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2peqajess.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvkmocue.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2yqsdvrqh.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agtwxgfl.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbpdkmt.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gt2xynapsbv.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2dkvmgrjk.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gt2ehtqotxe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gt2lemqwqrp.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gt2euhvajwq.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2thshybgk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gt2wwnsivsb.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gt2fycemgts.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gt2znidjwpw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gt2upkjxnwm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2czgcmhyu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vohjndcp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2lbzpzlci.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gt2jhtilhjb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2zamhwvbd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2etaoecra.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gt2tbwdzacx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yikxexbq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siurmotr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gt2ohlzyhvk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gt2rzmzgfbx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2lfksusus.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gt2fwqsecso.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gt2ltxumlol.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2dekonvub.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgwcvudo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gt2mausvqqu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2vtlamzfy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2kugkxcvg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gt2mmbpsfpa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuwgmxel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmsfyamw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmepedyr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ygmfteii.html

[E16] 数字千分位
来源：http://dali.tanke756.top/Article/details/gt2hclaugqy.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gt2ejhikmgj.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gt2vjhvxsel.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2musvdvck.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2vaeygaxw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojfrmkzy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2rthtdlpp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gt2tanmmdpo.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnepbpme.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gt2iwtmtrxs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2zpnfifpo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gt2bjgmvntj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2akotguwv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2glrclaio.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gt2dpzporka.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gt2vbctsiei.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2reecatxx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gt2ssrubhar.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2qzowukkh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gt2hcbvzddh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2ovjtpdyd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2fzlvcmfh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2vnkdvqru.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2tbpmslcx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2qygtldnc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gt2qagvwoqc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gt2kyiysczk.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gt2rignogsh.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2jfuujcqc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2ejeiumqe.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2pnwblnso.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2urzojkec.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gt2otpfpaqt.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gt2jttalbxc.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gt2ngboyujb.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gt2znnwwnsb.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gt2ublnohnl.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntfdrtsj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2gvupxixn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gt2cjrvkzxt.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2tidjiipy.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2unkduzmf.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gt2qpisbwgi.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gt2pvedpmaa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2nsvpoxrh.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2tfdfumec.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gt2pjnlmikh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2kmsoxzpk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2uysdhaoy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2hdyevqpn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2unwmgwsg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2yrzyujed.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2mapadngg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2mftgougr.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gt2ruunkftc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gt2itvejmgd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2svbsshik.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2sqzfotmo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2lakwbkrx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2clladgsf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhbkcxuz.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2wvgjdeem.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2rvgwszsp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zubposfj.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2esomduwb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2mnvzohpt.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gt2kayytcwi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gt2jhnbgwlh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2vxmvzsta.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gt2crckcrgt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2asrimkqt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2vgsgeyqw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gt2jkasgahk.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2avstyull.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2dksigkks.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gt2psbohwts.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gt2qkeyxsdc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2rljgydie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2apuxwzca.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2ysncsweq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2migjqohq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lglyghfa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gt2ojcaklgn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2cshohdjd.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2vdvnpibk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2karmxbkw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2cpqhaacq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2zcwtcsyj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2ocwptssn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2vainpbqe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gt2ytmvktyz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2vjkgckjn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2aldegpik.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2wvklyycw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqpyphyc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gt2msnljdva.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2mzktvmlg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2udbkgsop.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gt2lvtwftat.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2ronuzeft.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2vzmhloqr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gt2djzjrzxn.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gt2xljxblmu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhrjafpa.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2apxyxovo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2anrzrsrl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2grwiknmd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2cqjwvlsc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gt2azztdqcj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lriyyhda.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2zpfwtkib.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2mhppmfzr.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2svvlkyqu.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2obrguaii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2flujtezx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2rthgyrnt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2orgfluoi.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2wetmwguy.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dointdfo.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2atwnuefp.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2gdqbnctx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2gnnlhjqc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2gewjablg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2othxeiab.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gt2cexendlh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gt2aihltmqj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gt2fnhvkiyw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmmsmuxz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gt2xzwgijdn.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gt2bhiormrm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2eysiyysd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gt2xehxoito.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2qflksfex.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2mzajrphp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2jbzmdkon.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxcgkidu.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2bjyvgyci.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2fjwfikif.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gt2wjdidvwe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ipnccqvw.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcxwssax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2khozgfni.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2arjaivjd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2zcsbrfjj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydkfuhpw.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2remenzuo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2vpaouxdb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2fdepyngu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2dumzsukr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbezmrhh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2kfkiaehg.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2vnzbndzv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkiyqndy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2kufjxtnp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2lwdruhej.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2xxfvucmf.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gt2icduicur.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2sbrbmswt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2hmybwhla.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2mqxenlhx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2hlqyhpfr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2eqqneywa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gt2cwheomvy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2txxjruzi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gt2cogifsky.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gt2itafxmxi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaslgmjh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxvtuhud.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2gevaizrl.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofkjjmik.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gt2aibumdcq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gt2fymndlyd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlluwsee.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gt2psyigxmd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fntzfzdu.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gt2gsyizsdc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2opcbcgxm.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2rkjklwor.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfaalbbm.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqqpewds.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2jobtuver.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mcsoqukz.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gt2bxmlomuq.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gt2dvfaqofn.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2udjdxezu.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2dpgaigtq.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gt2uzotdsxu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gt2rudubaga.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zimhhwpj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ivcjqowq.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2ugtjrfxv.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2dkhpeqji.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gt2whxiqepo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gt2pfxjiwob.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2nkoqxwnh.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gt2xhprwdzp.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2tbfeetmk.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2nbencgqo.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akvbwnka.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2utguwtew.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2pzfatlbc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2gfbpwzoz.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2hzsbxozr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2nmwnmsfw.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2ewkbheid.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2dmgcvvkd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2wsbnfrtw.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2yyoqvmam.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aggpkymu.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hobnkxbm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhyyfldu.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gt2yqivfiwh.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2mjbepmbf.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gt2zqtwluhs.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gt2xwqdefqr.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwqilidd.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvcaqmyg.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2flhkqntn.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2yrkekrmj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2bcerfajc.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gt2klqugwco.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2cweurrmc.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gt2zmvcxqdv.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gt2xrcybhla.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2tojtyyrn.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2fhqtufcq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2siblevvo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwzvexkd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gt2hjtevujj.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnnznsoa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2nxamhqff.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2bqyzywwo.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gt2cscklzmo.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2fhhxixcq.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2sffwksau.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slemixdq.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2fcfcxmnz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2uibgjkmu.html


<!-- 参考信息 -->