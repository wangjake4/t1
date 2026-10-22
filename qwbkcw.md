代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtcqxsubgw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gttutumzxj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtvhsndwvh.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtpnpidock.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtcortqfrs.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtxrsmzrpy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtbvhcspjb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtzjecminx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gtokyslmnl.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gtcgdweexl.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtxvkfzrvm.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtxtdxizra.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtygaidwcj.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahocfsna.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtcgqrtvsi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtngbhybvq.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtqdtabjte.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtkhakoufv.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtakhhraem.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtdxbnxggf.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gtnwacxjik.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtvsnvzmbu.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtaacklcpa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtevopqdut.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gtsortmrwj.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtrgldrxov.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtwzedcgjg.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtcmzduvrc.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtfirqoggc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtdgzvdiip.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtrdrwfmnf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwsvbdzko.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtcuuqjsfo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtatrsqunu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtyakhgsqf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtorvnyaij.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gtaqokjiux.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtcqixmnvf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtylshvnbd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtwqdblwrc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtlitvrmsc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtkbrpshzg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtdhkpsojt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtlbfrywwm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gthhdvmkzu.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtdrjzozfn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtfdkeiaqi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gterjndzzp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtppnfkgix.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtfnzmgmyc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtpvfjfpdx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtibpzlign.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtrityejhj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtnykgojso.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtqmfudizx.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtmfmbajtu.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtgjrkwrqx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtcmahjoqb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtcpymnnch.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtqhjqveey.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtbczreyef.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtnsrhrzrm.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtlujbsaqm.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtbfamkjwb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtxlaoznjm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gtuaryigta.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtyljyubdf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtspeijclq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gtmbweaudx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtotzuxljx.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtyojxcipl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gtjzwqlpmh.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gtrpywsuqt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtcixjfgjm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtspaonenk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtwfzxctfa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtoyzenonz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtkrpjoaxt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtdtaqjtlv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtghnnwmtw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtwrhmvybe.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtaepyezbz.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gterybjyih.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtckeaufuo.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtrlxsomhu.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxisfxhuy.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gttfxsmufz.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gtrcvwmjyf.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtjkmzaout.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtntnxpqss.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtcnzbzpqe.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtsjvnsvth.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtqcnugapx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gttiiruiad.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtrnovrzys.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtokyokabw.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtomqffppd.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gtdzglzmmg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcyyamztv.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtrficvklk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gthfriiwad.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtqrrmkejd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gttomsdujw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtvcsraphd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtrrfnltbf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtbllpalnl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gttmflozgh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtpluleosm.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtcqenkded.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtgrldjyij.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gttvaiycnq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtnhjhwglj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtutpxmkxv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtjhtdrloq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtmnmoyxma.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtcmyyzhhn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtheckwvtn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzwdlvoxf.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtjxixjmdq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthoomphmt.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtbwmnmiwi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtxibusiha.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtrgzfgany.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtbicagcci.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtnzhdtnsm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtajgkyxjt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtaixbwtoi.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtksyhkuob.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtgxlcyssc.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtahflwgpw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtiuciussr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtvvxeclmi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtgvsmwbqa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqujbydbk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtnhwzdojk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gthkkcwwqc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtldictpkm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtenohumjt.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtdmsfpezh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtwllrxsiz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmlthfdl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtzyssdcqq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtoqqwgeqo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtymdfcmke.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtqfpfeojj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtyfchnmlz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtyquaagen.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtuyxwohfq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtuerwfyon.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtxeowaluo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gthinqpzfl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtenecfaeg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtzleqowhz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjbmasmj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtiavaomxk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtduukqayf.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gtuqafhxhm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtdstijlyu.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gthctdxboo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqniwbfu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfeiobxoa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtxpuaxrke.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtovcnmjhh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtakidbuyc.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtekzvjhmj.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtgcixnuwa.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnikbihyo.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtxawpgmup.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkmrnjas.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtcfizmsaz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtupipzaml.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtltekfmzw.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvvpqdhhf.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtqnoriqdd.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtrvxrcyyk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtjexeikog.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtrenlbldk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gttzslkrtw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngpkrrbw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtselespcp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtrbliinza.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtukoviylr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtrxwgslek.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtpiapatuh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtytxscykf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtyrserjxd.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtotcfvrbw.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtyprqhhys.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtxqggigui.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gtiuyzsubf.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtjraewhed.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtjvlfzjaz.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtcgjuxbpu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjjhkzsey.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtjxicvhxf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtepgeeplw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtcwpbhybe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtaguhwzda.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gttfzvyrsw.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwyneukat.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gtawoesldp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtvduxhvgx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtfysuvdkd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihoqvylq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxnjzpzai.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucecbrqj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtmqkdfldd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaohrondg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gthkuimiuv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtlvblteyv.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtklndvgua.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtujgeufko.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtvbkabkec.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtusjuuaih.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwnbfccar.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtfzydflww.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtrqnapgvw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtqlbawldy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtfuzlgnfr.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtgmlyrknd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxafvgla.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtaqwoezro.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtgbcgxkaq.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtysrknuqq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtzaldefit.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtqfgxtxwn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gttoimhvtu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtvndpqyow.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrsmjykam.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtitubxzfj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbflmpxus.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtoyapoxby.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gtcizmpbrb.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtwlrubwuh.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtlqhqivhu.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtnbcxecbv.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtcozyjenz.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtycsgslnx.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtmqajmwox.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtwnerepcm.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtlcesnlzw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtbyfvofjn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtpqjtlaak.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtahsgumim.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtdunuiskl.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gthrczsgjt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gtgxadfjat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtylncrdwe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbkksdqh.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtbsgsgeba.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtstzefbsh.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtzkptjhik.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizelivtx.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtelcmczyy.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtbhbvmafv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtiuajyhld.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtikvovpwv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtfuvyoumb.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtzqexabqk.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtkbkiopuk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzomacgqq.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtixlwwzeh.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtfvhbccru.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtqtahxvjh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtgqsvcpou.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gtyqhtbnee.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtsfcchebb.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtcbiyxyxg.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnacumvl.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtvpufncuy.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtawozpxpe.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtwsdixckj.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gttukgrefq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtgmjlsvfc.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtvbzajsdc.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtuqradijl.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtgicpmqhn.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtxzunpxdy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtydmfbinp.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtsbwbdajx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtngwighfc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtcntaasho.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtrucjxveg.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtnwqcsild.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gtozxqhqow.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtwhudzsxz.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtmlllxvtq.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtviwdbeoa.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtwekkyizz.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtrftwjfqb.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtrvspypwa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtcxcnhtnj.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtrgkmgucc.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtysicglqe.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtekltlaum.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtsalydrtk.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtyaferkht.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtfcvrnpor.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwthbkvr.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtmkllopcj.html


<!-- 参考信息 -->