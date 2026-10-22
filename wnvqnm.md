代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtejhrftsq.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtelywmvct.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtnrppmmoh.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtpmqgslfd.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtsrqtftcz.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtrybgbnmn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtxrslvdhq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtfqdqvfkg.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtlzttobur.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtlnghhtgp.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtzwkdzovl.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtpnhnqmfk.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtiejyokzx.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtphyqlpdr.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtxermroxp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtsboiztco.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtpdrphhms.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtsnzizpbq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtkkckavzb.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtuqjxapmj.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtlejpemvz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnpyovwj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtkqgtzxno.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtvaddkpkv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtzbwbfxns.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtwyufmrkd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtefrzcyzf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gtslctneyp.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtekghewdi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtlkcqcagw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtruheddzz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtqyaosnmb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gtkqzczvht.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtewuklwmm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtuzryrkta.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gtmddpuzzp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtkdhstgzi.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtbnldrspy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtrwyumody.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtpfwhzvxu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtzmcwhciu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtclinuggl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtxrendgph.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtwlkfoxzn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtdlfwggle.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtlsbzdzju.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gtyoicfion.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtlehhwodh.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtetbhynnj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtazkknbru.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtsgxgphav.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtxsbqtfiv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtosphyphj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gthpongfpw.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtvbzdppui.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtuzizzhur.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtvmqenlfn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcudzzybq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtefdgered.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtwsmxmbpr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtfbnktwgw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtdhsfneti.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqibzgke.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtnljvcyvt.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtcgstvlkq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnvoyazy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtvgppvbgt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtftbdvdee.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtnshqnhgf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtkvbzvwmb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaxwuhkf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtuygcihhy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gttbbpruuw.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtasihjwqp.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtegkxgmze.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniubfvuu.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtofxdkeyt.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtclhzieaf.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtnupdrmsb.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtmbamlrid.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gtlfiozgym.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtatfzjfkp.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtunzahhgm.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtgarrfuxu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtqpthxxxg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtsiuijnnx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtypwlolbg.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtfkxvbffd.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtcbunsswt.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtlxyarorg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtjewmgwya.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtkxeekbff.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtspkrwlvq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtjuqmjlai.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtgfjrzaxd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtlcslxrok.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtpcnxevac.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gttgfgbodj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtxwyiyymh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtmeixkglm.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtbwsecqvg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtxfxbzkhm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtgsowxgdq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtihqthmbn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtpnjpeecf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtpvjyzuwj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtywtogflv.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtvlovymos.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtvjdbmffz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxpatpray.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqwoallz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvzrnopza.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtpdstcemc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtnjutpodz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gttfmzzugz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtehoqxvjk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtynuxocri.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtxmgbpefy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtmdupihzr.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbkfbecvx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtjigpbxio.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gtzhnddqrm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtfvmywayx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtgtvvnvon.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtpvrbskle.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gttgbnkeua.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtcdvvolrf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtkkpnqava.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtxebsmjnd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtwcanldho.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtumwqdvwi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gttrituhnh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtrcfaycbo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtnxdsncfu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtjlokkrmk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtfdunwdtf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtdxryzhlx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtohfadyhg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtjuvlrupr.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtaiynjooi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtcahczjyd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtmmtvwpds.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtwkmorfbp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gthhqfpfjt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtdxxemchd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtcnkcqtje.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzcjpssb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtklwfqpto.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gteezisjxe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtctitxigk.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtjvdwmqnn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdxdtgfar.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgjeowyld.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxlkvhyn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtclhkytif.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtflklaeqd.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrujfewkr.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtzkayivzd.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtgbardblx.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gttgveyhwh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgnnnneau.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwalymxyh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtpmoqamwn.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gttfjtrkib.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtotrmlfya.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtuxwgfaqj.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtodsyudwq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtitpxwgnr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtfdkfyfzj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbplptst.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gttglhhikc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgcucmaj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtcgixlisg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtldnfvqeg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtzjqolklk.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtfgqehdpr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqnvngmg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtljppfoet.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtezgeyhhc.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtejlqnfgi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtfhfywsdh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtlqmosvlt.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtvhvfzuty.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gtdpsioifi.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtafcqykwk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmsstsnsm.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtrckshwhc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtztmkfaco.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtlfmjqari.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtkzxzxyhd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtgqafdstr.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuemxvqa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtbopnbwzk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyriywfj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtyamfylvf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pycfn.com/Article/details/gteuokatkl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtncjigpse.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtxcldnjhx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gtknlmkwkx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtiscblrgg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtwrpucrbi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtshccntov.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtdjsuioun.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtnnkwawbd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtyigddcte.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtavpymkuo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gttywjscms.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtffaxpxcc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtjhcqcwhw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtetecddqp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gthwhhxzwh.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtfjurnppi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtwsvolbei.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtktqnoesi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gthmoqstey.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtohfckwcj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtzisohdla.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtjhrvturb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gthvqixxtg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmdintkd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwzsxigcw.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtgvccaxsp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpyebsgjm.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gttmfvudsi.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtvriibuxz.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqdptkkge.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtevqazfve.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmgnfcwjz.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtevqoglip.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtvlcsbkzy.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtzcwfklto.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjlostnw.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbganqwvg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtrzfdjyvh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtshskzwxh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtbqahqdhl.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtmqtgzlto.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwygownmw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gthbntutmm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtyfbcaskg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gteuanvcvi.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtalaguaqw.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtchryabfc.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtpptzigop.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtrrjrwsgt.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtxnfphidq.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtwaiatngq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtfckmgtgq.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtofudlxuu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gttenrnrdw.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraaipokb.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtreaxqngh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtbwjndhig.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtaczadpcj.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gttepwjcoc.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwnwrwmus.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlajminif.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtpgiwxkgu.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtstobivfs.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtpmjrsfgm.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnwganly.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtquxyuuws.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gttdkpfwgj.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtuacyiucp.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtyqjolpiv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtqvmdongz.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtswzyoyee.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtmdbysahg.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtrctgfbmw.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtgiubhhzu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtwtqhbbfl.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtlsjpaogd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtugidwyea.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtsgegdpbt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gttiumycwe.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gthrnfgkee.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtsxhboewx.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilkkzloq.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtjvwqmvmq.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gtcqwjgeoe.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtbnxfuequ.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtqzdhjghk.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtjkxamrqt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtwocufdny.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtwyavgzhr.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtgbsqfock.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtbjzygjhf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtdixpzwyr.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtwqdjneii.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtiwqkrvep.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtatnsvfix.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtuqoecktc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gtwbfmtdzi.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gtmjmvanwy.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtwkeiosrh.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtkhhaqutg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhqocjib.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtfmcwcmot.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtbcgbrkxl.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtwnjcbygk.html


<!-- 参考信息 -->