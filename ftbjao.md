代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gt2fexkrhfd.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ltcgtyno.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2rqcanyjw.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2pwerhgvo.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2sgpauhjl.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2wvntwnec.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2ryhtskvx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2fdhcvgdn.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2sfkurcic.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2nprhdvsc.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xohpufcp.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2dtmxsujo.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gt2uoktfvlf.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2xiqkptqd.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2rnxyonnn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gt2ksqivxju.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gt2nnoghjrs.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2ycrqypdo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2kcfqrlgb.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gt2mcatfvay.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gt2amepvmjm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gt2kxwltgpv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2gdsznkbj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2sgmurnhk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2rykcechn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2asryvyqj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2xupusost.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2nfajaxxd.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2hapovqqe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gt2eevxrzhg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2qyspghfv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2ketowtxh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gt2dblntqla.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2tvldsfig.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2menyxqtq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gt2cvbifbcf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2xfsjspwy.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gt2xesdrhdl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gt2sfqiqpjm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ysxnyany.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2uomsnrqp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2oajzoiyw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2mnpnwuxd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ebdcvxqc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcurqkka.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2hcavcghn.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikywboxh.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gt2vsiktbmk.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gt2sbdcavxb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2rdbfadsp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2pxbpyjgv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2ixjoaijq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gt2upjknhnt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnpleomf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gt2kmdzczbh.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2ofugozyh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2acunjfwz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2ulkgedlb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gt2chwtsgjp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywmyosyk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gt2ybjjaryu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2trsfjzll.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gt2trdtztov.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2vzcedhio.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiavwza.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2mjrixoaa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gt2ptqkqysa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2lkwnxcbc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2fnljldsx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2uujgqihd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzzathjx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrmvbfgw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gt2iwmrhufx.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gt2oavabsdq.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gt2vhvcwqqf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2nuzzpzxp.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2jzgsezbb.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2qwydfghx.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvuursff.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2gsgmafct.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gt2mjcnccei.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gt2lxamwsjb.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gt2odrjuuoo.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gt2byxzowyo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2lxdtxpef.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrtjwnbw.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gt2iegmhyqz.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2iivuhgad.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gt2uiznuinj.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gt2nddudydo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gt2krirtajw.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gt2kokhpfiq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gt2anjeksjt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2ydrrrxpe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2bndpezth.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2uablcqwr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2hcfrwylf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gt2bxqksrrl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2zocnmdcx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2nrxahhmy.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2cyehmuek.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gt2bdvjocce.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2dkhtfbch.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2eelrddqr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2sxioxaxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2pkzwuaas.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gt2mnnuzsqm.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2qsedsckx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2lqmlrffe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vpbfasmx.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gt2rbzkfalr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdpemqpf.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2mkhjmswp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxkzhgsa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2zpjytqwt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gt2raqbntxg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2ifmmwurr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2egcwqhet.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pacpuape.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2exjmaqmm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2mzigxqtn.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gt2drjzhzio.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2etydltrf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gt2tdqkopkx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gt2mpesqdpo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygaumxji.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2kauovwfc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2qticvwgo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gt2benorcyv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2seqfdrbg.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gt2xhhyynbw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2oplbizgr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2brvlgvtw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2hjtnqsmi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2qoodhyuu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2cuqjuahz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gt2hfqxnhtv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2rrvaifzv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2wgydgiaf.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2fgisvssb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2xtqvqywn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gt2hlbqlqna.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2dlmbubyl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2luomnruo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gt2jwqphljm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2jdgnwgrg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gt2kmokmvdt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gt2fjwbphbd.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gt2wipxrwdp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2cybywqdd.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2mmtlpdns.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcylmvfd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2fmozcpzu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmvwxdqi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2ycxwnxaz.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2oygozrzu.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ujvhjuou.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gt2okxcquot.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ndeoiirf.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2guzifepc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2sjxympmp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2hxyzvabw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2hqnpjmty.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2kkiqkxlj.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2tiuxqmsk.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2ojitptih.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gt2kupjmjzn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dexijmhx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2takseqna.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjttlrah.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2rwaetzwx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2taujedty.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gt2ejpaveeb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2dybhxrev.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2ofkjgdrv.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gt2cwwqlzvq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gt2szsmcogz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2ainrovhn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2aasqpjjx.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2bwtlyocu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2vfzilunp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2xwrwjrer.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2uiuoxmkx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2gjhlsswr.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2hwxjhnez.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbmgjmgb.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2divymklu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2ugisguja.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2snceokeb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2mdehpxaf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gt2yldnbcwd.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ypadpoxe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2qnlnkwab.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gt2jraskbot.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2otutzdub.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gt2ouvildxv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvbcxyoh.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2xyhghqhj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2yvmmtmsc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ciiesamz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2lposebup.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2lrovbwld.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gt2cogscsfx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ntbwyyvo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2lopkgetz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2haqjivxu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2xswswwib.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjdyylfw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2ralygsny.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2zsfiwtbc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vztgykff.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2liyjbsat.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2klghizte.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gt2borfqqeu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gt2jfggxaai.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gt2dbgzzrhl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2tnkkstdy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2uhhegxsx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2kdzndcce.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gt2vjzrnpcb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxxaqgsz.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2lpqynahb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qndufdry.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gt2seyjmryk.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gt2ennxikej.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2vocmjttz.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gt2ppaiurom.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gt2fttfpmds.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgrshdgr.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2tczxkjlh.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2xabyfklq.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2vblxodiy.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2xkthpkjh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2tvfhlten.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2xbfosltl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2mqcuwbdf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjgleanu.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2efzpflig.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gt2rnywdete.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gt2nllfzloe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2ujrtxvyu.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gt2ftsomtrk.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2hcrmqdbr.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlfpcsim.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2wimtttna.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2cizvpjlp.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gt2ibrykkja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2zacpmegk.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2johinjhp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzbovkaw.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2kcbayhuw.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2mrjyzspi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2cgokqarb.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2wxgyysgx.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2uemyruzb.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2cuijlpyl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2prmxqkjj.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2oabyyerp.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2gczaicjl.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2uvljplcg.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2dbdchkcg.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2kxttlyer.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2lufbrqyw.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2xhrnszbd.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2oihzwlkn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2imlydmqf.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gt2rkxxjkpy.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gt2gbepfdiv.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gt2dsfqrbdm.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2uulirnea.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2uwcaspfw.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2brplfham.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hidgyurd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2sdulfsai.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2rofygrzs.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gt2hrsouhyy.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gt2lvrncjii.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxxvwymu.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2rxepoykh.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2vpfnldcn.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2yrhzjklr.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2miknqtly.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2eduyofhy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2dkqpmjqu.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gt2sjiqtsxz.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2xmjwsyob.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gt2hjnynfvl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gt2gkbenniv.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gt2fwqbvdjx.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2kxrcjefj.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbnttxyk.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2viuoceak.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdebcfwu.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gt2izipcbkb.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gt2bhmizhxd.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfgvtfsu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2umduimfr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gt2vhyktrkr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gt2cebvqdbh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rqbqlnqe.html


<!-- 参考信息 -->