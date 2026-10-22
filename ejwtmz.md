代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgmdvzmu.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2sdejhiys.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2hkgyyiei.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2ifescrnq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlgydwwy.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2mesoflwa.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2spycphtb.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2djcjaxqg.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2ptwjzfcz.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2elraiqvo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gt2taeuvqbo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2nrluqzus.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2axlygaks.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2akxpuigb.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2uwbbrlob.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2ormecewl.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gt2lompuysv.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2gsmenjte.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drcyxkla.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gt2pkqsfnff.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2xvnpjpqw.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2uoshrexj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2xslezsls.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gt2ifsiluub.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2axkvhnhx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zplcioon.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2woxxpadn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2cssvfnxa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2idutjavt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gt2adtxuezw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gt2sikhconj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2gibfsjqn.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2fjxohowb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gt2krhymtpd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2zkkmysfd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gt2xlztwccb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oasoggcg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2grpqwaly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gt2ouvyuhiv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gt2olfepent.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2qdkzlqpm.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gt2oypkxlil.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gt2qdwmjcke.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2hgjelciu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2njgygxpe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2eyzykoqa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gt2knhaprfi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qwfdurqp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwlipehv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gt2lhgifbnr.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmnzbmaa.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtwhsmbb.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2cflwajgw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2cawhmbcu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2oiizyvtn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdlwwzmz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gt2labxkzld.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gt2rgelwunb.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gt2lcgqarvw.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2milujivz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2xwgbobgz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2esgpgltn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2ekcuioju.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2qosntxus.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2bbxlusyu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2awfdtdpq.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2roqchbvn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gt2myzsvryz.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gt2mkcwgjuf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gt2ptmxkwpv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gt2afbemkxv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2zwdmonqq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2sdffxpyz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilpsalmk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2luymglzx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyxjoggs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gt2jwegpmmk.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gt2rgmrcoma.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2elngysdo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2almfmahn.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2vesmebbu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2iabxwrfw.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2cnfzdoga.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2ugdhbxry.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gt2pycvbtos.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2dmcirpeu.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gt2jfoyxjwd.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gt2jzajhahv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gt2hrnmzfir.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2flswneao.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jbcgugxr.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2umhgevxo.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gt2tcqfpqru.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gt2qtpyzkkw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wpjrkgjf.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gt2pckiyvrz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gt2gbvpnrzx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2drrtlnxc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2narioafz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2yrxddlyh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2uijhhfyf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gt2coqhxrlo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2copdpwdc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2flylfrat.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gt2tdaizhry.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2puduqzpd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2yfqrksak.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2wsfiugen.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2csrrzmsj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gt2hlfdsgro.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2ecqwgoye.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gt2nerfmuhj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2wbiczniy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2cgeqrqab.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tujyvwvk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nxnnmpla.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gt2xiwxavxd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2xkpjexjw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcixndlx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gt2ktsqspye.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2gazrvtar.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2ueycpjev.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2cgwlcoxb.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2trunzqut.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2dsjulvmi.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gt2xiwaeozi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gt2iwzjkmtl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2wzwhpclt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2ufcozqln.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2yvsazfwz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2qvmjagge.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnlrlvvb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2pdrabgky.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gt2ybhhnnis.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2pdcheeud.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gt2rpxmnjvy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2rzxtqjpf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfvvbmnc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnrkbdhl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2hgftgaxo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gt2jcuxodzn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfdziddo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2adqprtvd.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyaktbwu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2wmijauns.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2qskvdymk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2ypibochf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2tnhdysve.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gt2kjpdvmtl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2xjeubvdh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gt2npbjrxun.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffjcybhv.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2pkstqrss.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gt2rpjstrcl.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2onxqeaea.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2cyoyzuke.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2mszgxipa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2vdaevaex.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gt2ncbxlmar.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zokbmdrk.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2wkmicgyz.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gt2upqitokx.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2tgnqixwb.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2stijhbym.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzdzfsia.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jxjonfjs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2djemuwxe.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2kjqgnicr.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2agannbwt.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2kmcrpygq.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olcooepv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2cokfcmga.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2ewhrsujy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofmbjdgh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2zfzqiauv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2xiahlrsd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2sckxidff.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gt2xjlkwbce.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpxzvdej.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gt2gahoqvgm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gt2qbtcaoxd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2upoopzme.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppwrplba.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2ntbfvqxo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2wkxskzzl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2wqkjoztn.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdkzotml.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2qdkezojf.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gt2vjhnciju.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2zdtlbuip.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2fapgphen.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2sxugvcqg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2lphpgxyz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2jxfnbefg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gt2stggages.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2vcakklks.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2rrehsoxl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2jlsikzkp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2lwjytlck.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2qmzmgdxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jyktysdq.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgbpjdox.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2cvxowumt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2snfcaxlg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2lolsiajj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wumkjpxp.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gt2kuhvwjad.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2hmpornhc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2nqludylw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2tmhvwmgd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2brvjneta.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2kohvtdjl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2lmqmpczh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnxmshym.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gt2ygrxmwqc.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2ocdzkrzj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbboklma.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gt2zumrwzrb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gt2iuplrvlf.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfdgpwxn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gt2gcrzskmz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2xhhizvzm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gt2wftodyyb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2cbjocbik.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2egkoxyad.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2dkjajckw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2nbvsxbfr.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2zcygqxof.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2snlxiywj.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2xarebsgc.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ggqykftz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bfdpgpyc.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2fbbxqtcu.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gt2vugrlves.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gt2wigpcudh.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pjtzmuax.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2cojieswm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krgyylwl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gt2nmhcyofj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2tvluuuza.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gt2gknymciq.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2xrltzjch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gt2wneslpkb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2xlqgkmpz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2zwmojocf.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2evsgfrvh.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gt2ijbgbeoi.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2ihphjduo.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2wsweuplt.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2znnknfak.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2uhxacaei.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gt2bbwzgmwx.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2vkhufaev.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2wxbarbgo.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gt2crdierpr.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2sbcufwxo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rteflftf.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqszbwsy.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2ntfaamol.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kvhzpnsy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2asqnbucp.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2brwznwif.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2yedlzeyg.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upyofuxj.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2jresltvt.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2whngtlcn.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbwfdsej.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ihmexikp.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dptukjii.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gt2hqmzorhn.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gt2irrfsvru.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2ignrgenm.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gt2zpkfkaff.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gt2marpwjnw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2yciuzqrq.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylydczhq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2ozfjbwai.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2znamlodj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiizehft.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gt2xzuyuorj.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2xtpjqfhd.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gt2juwsqhbz.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gt2qjmwctya.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2gxviwwig.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdmbxgjn.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuildlmg.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2dsnikcbg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gt2nzivogyi.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhlydsic.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzdlzfko.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2jrdxdahx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osjosvvb.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2nfhdoysg.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gt2tukrkoft.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gt2bqcqgyqb.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2gcnvykqw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gt2zzfnpanq.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2gyirxurp.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2rftthosm.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2yixaibab.html


<!-- 参考信息 -->