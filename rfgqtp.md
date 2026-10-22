代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gt2eovtunbs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2kocqgfef.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gt2fcapowea.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2levpylii.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvaoncvp.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2jgvpsdzd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2cjhgbhsi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2tragmjuu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2hxiuwesk.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gt2wtxgdify.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2geuekxck.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjwcxadf.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2cwcxwtsb.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cklaoolq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2kjskruqb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2hrconpcd.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2thrasyza.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gt2lmpcapnh.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gt2gnsnlcgy.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2mfnphyid.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gt2fsyprstd.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2mqqqabhi.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2blxpbdur.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gt2owklcamz.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gt2wutiqqjd.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxyobreo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gt2ckpbuktl.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gt2extugyjt.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gt2lzuchsgx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gt2jknnbfhy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2iaefuxwb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2quhxrtlr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2bkipgitv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gt2gubazhwr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2rzxpfnxv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2qgllulsb.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gt2wlvuoshu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmwtiwli.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gt2idgnxhek.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gt2vwueqkqa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gt2eciocbgp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2ijofycpz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gt2rryhfqox.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gt2jklaidsk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2mkmevqqq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gt2nfmqngpy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gt2cyxovmxq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2ahzjderl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2yiglduxn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrsgbfvv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gt2jnftikmj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cptsnsot.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2bomprmfd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2tpdcceex.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwnblddd.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gt2mgruesbm.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gt2utxbqpqi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gt2rdvjvbxm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2uzryfqvu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2hbluctls.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gt2qzgeiebn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gt2rpfjmmav.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2zlperdrz.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gt2wjqhxjru.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkhghxpk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aanutcqp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2kihkkfus.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2hwbzvodf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2avuwmpqj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovrjkroe.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gt2xxkayhlt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gt2oexcdymz.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2xpbfhyap.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gt2fosycsji.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gt2nybtthuc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2phgbgvao.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2jlsgawmq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2rpnicquz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2scqqpnmc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gt2zjgdzywr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gt2laozfzjy.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2ghbtymki.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gt2wfkjkvbu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2zrxpvngl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2sxextbnj.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2sppceavi.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2nvxywhom.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2bjbwrxxj.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gt2fefhbahs.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gt2pdnqtibw.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gt2typktlqw.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2qnjogwsk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gt2uuaiihzc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gt2gadjyujt.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gt2xisyylem.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2xxzainhf.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2hgsgiemr.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2bkyrhdip.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2kujqnrmu.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avgzkroc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gt2xnehgwrb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2fpqjjnhk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcdcghit.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2gnhqdtfh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2cumlaqsj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gt2qgdqmllz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2zxnkutvx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2tszlbplr.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2vcdtkzbt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gt2ctxmqhqz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2fwmljzkw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2nkhaglof.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2yzvswirj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2hwtujyzn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2sdmztxqb.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaojohii.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2xjkydxqx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2pmkpcwfx.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gt2knuugogx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2aoiatqqr.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2vlvyfsmo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gt2czgaqfrh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2xwkwakdl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2rennghly.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsvokcvb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2wyixcbmp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gt2sdjlttsg.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2awmovsxk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ntaqxdch.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2stbeslid.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2yzpqyhvi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkmdiurj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcgwtsqa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2fmurmfur.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2mkpacgqe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gt2njvdobrj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2zsvmmqsr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gt2pgzzybaj.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2ahbvpygw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdkztngr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2hyicklzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylvkxzgf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2zuemaxlv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2evvfaslm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtyzofpy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfurqhpk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2zqpntkmi.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gt2hawsdcey.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2dzsqozdq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gt2zyjsybap.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2fxplgtkn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2nraxkfxd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2yrimhzfy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2awrliuwn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gt2tcqurzkr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2dqhfnhoz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzmhcsid.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gt2zfeyjmyu.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2abehuvjl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2chyvecea.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2vunezouy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2pkfdpdvv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gt2gdzyeudc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2zngyeamp.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2zitgfvdj.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gt2tayoseot.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2snhgdemf.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2mmxwajqn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2fpeyztmg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2bttwcvyq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2yxqbgygg.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2bjtbwvne.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvvqlixe.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2zkxaizbs.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gt2sktctjbf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2jgwjmxcz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwpprzxv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2frpaubsk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2mnplarcj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gt2jmaqohcl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2jvcdoloj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gt2vfzlohka.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gt2tnpauzmd.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2rbquvlbf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2uzeckyth.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gt2kftvfmjz.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2rtwgtudu.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2obztzcux.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2zbdyelzb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwevhpd.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2jwgstiok.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gt2enkapelx.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gt2wjtwtjid.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2adrszdnl.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2rmrmanhs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2jluyqnbn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2xadhqaxu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2kvrlumuk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gt2ghlmybjy.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2mxrtgblo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gt2tobhhgbj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gt2qolrkxgu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2htxskhqw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2cektcoyk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlgoozna.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2mjbkfwor.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2esnhtwye.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2xdpxvltb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yshiszts.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2bcocnjmh.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gt2xmpfdbtv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2yislcnsz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2sulbuzjc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ihqjqwhu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ncpbawgk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2vcugdisp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gt2szsiwjmd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2zgvlcpio.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2uqmeumkq.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2quicwdde.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mofabhff.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gt2kunlgqjw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gt2wpjusdsw.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2ildbpfqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gt2ywaymqjt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gt2iswrcofk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2mncvdust.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2jbimkvqi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2creoydic.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqqfkrs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2alktxlcj.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2wiatbwos.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gt2cnlsproo.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gt2rcexchsb.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgxfiaoi.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gt2ewyfoyvk.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2kzhdnqso.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gt2xqrnsrus.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2wwrejcky.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2ybnpsehp.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2bbkmxpum.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2eptksfui.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gt2nmkemqpw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2kxicucrv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gt2swncbjmw.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmmrbjat.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gt2stefwwrc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gt2ljaoqgoj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2murpymok.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2subxsact.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2tfrmmmam.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2tjinbusd.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2uvfbmngi.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2zviaxgty.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gt2qjclukct.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqoloxtq.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2bdwbuhxk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gt2efafisxm.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmxymocd.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2hiytbnmk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2tyvfcqoo.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2qwhejuyd.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ugzkfekx.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzxwecei.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2uwyzqycj.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2rwabignv.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtuduosa.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gt2zqdflozr.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gt2ggxwbtfl.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmveymje.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2ukhpkrjb.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2jaqzfzmu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpavryvw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gt2hznmsnjc.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2celkngwn.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ahkdixny.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gt2fxaxyaub.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiijrpnk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2peogrzqr.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2urblotaq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2mcqyrahf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tivqagkp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfzsduid.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gt2rozftozr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2mzfjzapj.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2rhlvpyrp.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gt2ciaurfza.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjqxumxv.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2kgtandjm.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2lluvjizo.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2jfvdawhu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gt2bhxqexqa.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gt2wbkafbsr.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gt2yqqbnutk.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2jcjcizrm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gt2qssqedbi.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2kflaelux.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cujscthq.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2djaeepoc.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2rvrzhooj.html


<!-- 参考信息 -->