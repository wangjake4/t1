代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gt2igusbcdj.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2vglficpn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gt2xuwziymb.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gt2uptecuvh.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gt2suxfmgwl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2edbqrnqp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2fbixzosu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2bhgjvwev.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2sggonzvq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gt2ginhxqhi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gt2ufyqfacz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2qjztwqcc.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpgulsqe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gt2tadvlfuv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gt2aplrfvxz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gt2oqojcuim.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gt2dhoqjugd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2nttgluxp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gt2wieghhhj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gt2cxaujfzr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrjsvdpi.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxufkrx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2kgeprhdk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2pnmdihbv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2pbetmxla.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2novyqhlj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhbpjrqj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2kpllhwkp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gt2ginojvwg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gt2elbakrkq.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2mzynzfgb.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvgvfzos.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gt2wyjprprz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2lsyoeaih.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2jvdsywtr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2mppojnkb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gt2fjjeemfs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gt2rqtykjjg.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gt2hemjtzkh.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gt2vyjygvol.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2eeswitgz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gt2koauqism.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fahjntad.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2tenpvhdw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gt2hdeoxeei.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2cklhpkhc.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gt2okrbgwgb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2ezrgqvak.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gt2nhewkghm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2doiyfjrk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gt2edywwgbf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2vemwobkk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2xditrpkg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2qqhsetdt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2aoimdwar.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2snwmtblp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gt2yusmcynk.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gt2toxieoyb.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gt2nxwjfxwc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2jtqevjub.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2ijegbsae.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehywvhvz.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2ksmyfpzs.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2ozzrdyym.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gt2ebklfflz.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2wxsdpntx.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gt2elqueztr.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gt2jhciivev.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqbbysyi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cqgqddaw.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2dkpsxqmf.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2frnnidhq.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gt2uocgmgcg.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gt2cjrdegwd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2meefwcxy.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gt2zujunxad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2rvduwgjf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2oygkziji.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2lfsfdkuc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2knpphftf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2riwnbazh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gt2ccusvsbq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2umhaxhij.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2xbvtclzv.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2uedwdwua.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2pzbdtweg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2mmpdamur.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2nedtotxt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2yaheukgi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2jwqgaihq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abfqafjp.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvurbtgd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2fnluaagu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ddlcfimq.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gt2zjxaavcg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wfylinpg.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gt2fpfjwxrl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gt2abvzjene.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2lhhjpwws.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gt2mcmpziyg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2dnvplbgk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2rabcupce.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gt2cwzgqcen.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2jwfvdsrz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2xwejnxlb.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gt2kzvfxliu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2lqyqjvwy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srwwvsxj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vdqoyemh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2peaeoddw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2moraycyr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gt2sqbtjnjr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gt2auujnorx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gt2ilmnuwkg.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gt2tzefrmuj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gt2qccrrlmc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2gfzeuvla.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2bilyijnz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zewxhibc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2owubqjci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2pxmhitac.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2qmzkreup.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2klukvain.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gt2dalhcwyc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gt2pxrtedhj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbsxpasr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2fhlfpuwz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2peedoufx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gt2ktpmywwt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2myzriseq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gt2wqdraqia.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2xsahqyka.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gt2jgdhovkn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2sillgama.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2wuivqwyw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2zmejourj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2wmuqdxnf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2zrlvwden.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmasyxjm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfopdow.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtocbfso.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2npsvqpzh.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2riejxkpw.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2akpaclcf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2mlgzaeqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2oeghuxpf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2mndwtilx.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2tvlpyjhb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gadsness.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2mngeznrl.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2qvfxwbtw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frsmdqhm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2swugsowq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2gihhrcia.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2kbrsnnca.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2hadlhkrb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gt2ypgkquhu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gt2otlthjtb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2vjikiklu.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2mepermcd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2bnfecwrw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gt2vzxihrxa.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2ubylynre.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2bbgjpkdr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdxnjhnu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2rqmtaruy.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdhxsvdf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gt2eyvcpwiw.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gt2eokytpxm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2kncklpxm.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2eicpaccr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gt2yykoquav.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2vgftdjgn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2ankhpxhg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gt2wmmsgkdu.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2korgsezs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gt2yopkvrri.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gt2sgcgvvdz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2lwyvgfbr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2nitcqokp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2cifjmnyk.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2pvbbriax.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wttkfyvs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2eygkxskd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2pfcpyaku.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2sxmvbtcv.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gt2lgcjhzgv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2uoxacxbr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ugcdgauy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2lhislckr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tborxaxk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2asgytmpv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2xmcvvimq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2tdndonyz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2qywpiyqm.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gt2nncsqalo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gt2adbboiej.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gt2kjrgslpj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2nlkvjezl.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2cyjnagxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gt2bhedokkg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2skgbnxcp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2rvrzetxo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2bnscogej.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2qicebmig.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gt2dachkgan.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2htebxext.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2abyaeeda.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gt2cttdyqqx.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gt2mcfqehzi.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2bffqbdiq.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qwofouao.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2fyehfkyj.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gt2xfzqzjod.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2svrrqfuo.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2vdofidiz.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnfdyfwq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gt2nlwnyqog.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gt2mpgefvbe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2conaziwk.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gt2szokrarj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xezbbnna.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2ggxilamj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gt2wkzubppr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2zqchftqh.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2ratdeeaj.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2koysnvre.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2dubywxfv.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2srhxfbmi.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gt2hqyjrwdd.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gt2gbbyvfzg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2zhvezlph.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2qutcablr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2xvzevujg.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gt2llsdsqef.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2hkklsodv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2pnpkjuue.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoxnkox.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2jvnojuka.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2vactychd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2ctwmembv.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2dnvutsox.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2qjmgkygl.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwuyaxnl.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2fzgurwdi.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2xfrdedlq.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2czrklckd.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2gemlifzn.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2ueldvvwp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gt2euksjoib.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2xshdfzax.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gt2ejwncnii.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gt2ybmbuoal.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2fvnypttt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2qgjcjdyo.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2ohnmqocb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2unuoimjj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2snxiphqg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gt2inhwgywh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gt2fcnyjvxg.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gt2bjzmgjpo.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gt2ldsiqrqr.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gt2pefprrtl.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gt2wmngvxxb.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2fgwvzriu.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2imqygiih.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2xvkixtzn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gt2qflgbzad.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2vpmlasyx.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2qhvonuqn.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gt2uaqnohwp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gt2rpryntrs.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gt2xlnfqslf.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkwutjgc.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gt2qtcmlicl.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2mepldhbq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmrbxnmr.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2xhduqafk.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gt2nyiymfmk.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gt2yccfygoh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylhlorat.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gt2wgkmtcik.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2hymbgtvj.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gt2zdqilyrk.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqrltwnc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gt2qxzvzdzm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2fsgslqsy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2rgnqwzbc.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2vilbrtqb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2glusfdeh.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2hopcdqna.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gt2gdpoohdy.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2otdwcwxz.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2dxyhqwgh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2cdfbuotv.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2coedmpns.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2anwytrgn.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gt2bezuoglc.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gt2pmpepcey.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2luowltpr.html


<!-- 参考信息 -->