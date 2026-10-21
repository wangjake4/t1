代发 wailian999

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtvodewbye.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtnxayyyru.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlznsslga.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gthjwpsygs.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtxceopeju.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtuycfnfdz.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnlfgtvs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtjctilaca.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtxoqebubc.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtgijkzkxf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gtsdnfsfiz.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxezjenpq.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtqxuufzxg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtmznrjziu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtltxowxnq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtzwgpezac.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtiwqysybn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gtjwogkhfg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsmxugqz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdbpaqgs.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gturxfzpeo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gtumxnkebg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtanfaixfm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtsfithttq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyepmxkq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtczrxmeqp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtgrirstfl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtxlkwgrdm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtsvoaelku.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtsgjfkgpf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtcnvmnliz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtvxyputcw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtyyvohfrn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gtecpjqqzv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtsgtlkiix.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtxgssjlbc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtkwiqoncb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtemedcczl.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtqprysluu.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtgojbyvtc.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtvskgunqb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtuyrztjjb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtrnialijz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtnmyluwwu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqogbqyp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtlpnuhuem.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtnwnulnpt.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtusdkshft.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsfkaoik.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gtoysdgnyd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtoxvfnuae.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtmynbcxve.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtkfxkuhbl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtsxckyaic.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtzwnqkdxn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtxriztase.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gthnimwfcu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtinjbavcl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtrulywnaz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhcsjdqn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtxiqbbllh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtlrqrwzku.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtiibffhfh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtpzkoezay.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtdtzemieh.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtzqmhdjmw.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtvakxicii.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtstzxlcpw.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtbwjqbgsp.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtljvvxqve.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtpidpimxq.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtywekqyhe.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtxdqdtljs.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtcsifepys.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtauybexnj.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gtfeeqhjxj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gtepgaabxa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmhikyyj.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gtyunaleof.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtfqaauxvq.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtldxmjhkl.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtqxybivvj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtbwztrnrj.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtgaylvpdg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gteaxxtogq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtegmiibii.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtxcidlqnd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtvnjwbflx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtjwmvtkpv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gtdfhugtem.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtborwplvp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtorqrerph.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtfhpnkvds.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcfhzggru.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtuzgapeqr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtkkqvajaw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtowokxwjp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtaxqkfbbu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtwnoisfey.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtuyzmrloi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtowotyaca.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnbzlrjr.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtdwjtxisk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvhbbcfaa.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtfjgwekyn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtecswjttt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtdkeuuphk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtzclqgxhe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtfpvhhpbg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtzbpjcpum.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtnjvjkjyx.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagwvynub.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtsgkxzsjt.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtcwjsiqoa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtysmxuzae.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtjhlnjfql.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtalmhqgca.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtahdxbcde.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtwwswfhpv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gttifuagkm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtjtnkztpq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtomsugnha.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtatinnqrh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtjtshyvpo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtsuphkpng.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtcehuwzue.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtkoyuvlbj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtikdyyabb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtcckecuep.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtosdbnepf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtvswynfnn.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtyrhimmyv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtcflqqdwb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtusnqlxhg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtjplafees.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtziegkiez.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtlhcgfnqb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtymorrncb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtjjpnoiop.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtkepkrpto.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtobfwxrfs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gtxrbjkvew.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtjywgqrga.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwvimxziw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbamlszdf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtixwrgjuw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtutecgboj.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gttajaiwvo.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtilurysnd.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtytwqaqep.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtowlgoqjt.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpymanim.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtaiznjpmo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvgvbxlui.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtnfdignid.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtcbqqktbs.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjmtbwxnr.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtcswrtkpr.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtlffgkftd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtstsygedw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtoaskmfie.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtvpriwmst.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtovfnterg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gthidezdgt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtukzsfdsj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtnpxjfptz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtbdqxcpus.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtsfffvccs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtczuoftrh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtzzuquowk.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtudsrnxnz.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtqydakwua.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtpxbjlqsp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gtoyckpkuy.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtljgdsjly.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtwyujhbip.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtxzkclkyg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtdigogyup.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtvvmiqmrg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtxlkedfbb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtasjfehau.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtvjuwvuxn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtljegmjjx.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtevmxntvx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtzfqukxfh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhdmdahw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtsnxhfyeg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtgzkueeer.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtknkemkyk.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtbxzaimev.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtzpczqcfc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtobnfqtgm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfobdldsj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtzolcknwg.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtjnfnnqql.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgovvgqtb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtmyxxnvfn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgexmuzmm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtggnbsvhx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtccebhmlo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtxokxlcxa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdelwwupi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtlaahfvxe.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtwiascphv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtencrjllp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gttzhzdrxz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtdsvcubuh.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gtfqwyyfrf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gtmzizayrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtuwxzkagl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeztabsx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtdtejsewg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbvvaoufz.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtfpvjtqxd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzxphbajx.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtkcpouadk.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtlevidhxd.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gtzhaxpita.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdsfrgnuc.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtutgbcarv.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtgdllszah.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtgwmjnowu.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gtffihmrxf.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtdvmtxdbg.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtesuvasjd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtkyfwfvet.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtjjlqbdzq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtrsecforl.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtqymuzpzb.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtosxkhacf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtetwlnlan.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtyltlxmpz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwiqsxtyq.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtdjovkosd.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtsrzsfvvo.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtlnizcwga.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtaatbfyam.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtldbtliyw.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtpjglqahl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtnctmtcjm.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtqhjabzap.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtfmxephnd.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gttijrmxkt.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtxdmxuzmd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtrkggbmpc.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtphaesqzm.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqwdrqish.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtexfgqniv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtbnavodkm.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtnmjzrywj.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtmjfifaho.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtmrywxdjo.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtelrfvzpf.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gturfuhnzq.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjtrvwizs.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvuaywcft.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtvnmadmxh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtuwcvnrvk.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtoglyqpya.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtzfosxitp.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtiddjadmy.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtajohbpsz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtbaepechy.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtqyfewqvt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtpnsiunqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtaagtnkft.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtdbbqklvk.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtstljvxzb.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtisllmzgg.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtpxxatmnp.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gturcbyuyr.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtoubhldvq.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtenxzunow.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtynnyvfvs.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtktnkcrix.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtqjsveynq.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtglierkxz.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtewtdufpm.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxppouvlp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtqdihdqmk.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuoiapov.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gthmnqprit.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtyrlphinm.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtcbdcrahv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtigllbefo.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtbmdftfzv.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtbwgxonlr.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtxktomscl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtwzhjlcea.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gtyxikkyxl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtahqwlmcl.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtmymrsivt.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtbsbiulhm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtvdgrnyqk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtcohhnohp.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtsmwvvrum.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtjmrmixnl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtcybhlgzw.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtabfyzooe.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtaylkoeuj.html


<!-- 参考信息 -->