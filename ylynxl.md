代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gt2clxynbka.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2klojuqrc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2zdtafduc.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gt2vulfqmro.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2xnpjdzuv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbbqfglu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lsvxdgae.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2unzfxldt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2czrnpnnc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wppaerjd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gt2oupmcblh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnxfjgpl.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2txzlrdxp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2ivomrsyn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gt2smahpiur.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gt2mzzkdbbg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlhypmlt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2cgisidmw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubvebpgx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gt2kekopwqf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2xqvujgqi.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2cxbcblpg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhedfrtl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gt2oclyseiw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gt2pvfxkmdz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gt2toguuogb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gt2vqrkmxcj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gt2itftfmdn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2bsehjimc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ixuhawoh.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkqyuyum.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaxzrhhc.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gt2zqejsldw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2djhpyngz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2igmlyrgh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2tcxxtgcc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gt2hfnsqkso.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gt2wiwodxeh.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2aecyocte.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hztyuykd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2pgzizylw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gt2dqlpfkku.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jurryved.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gt2gxkmxvqm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gt2kpdbdimp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gt2ayyclvqf.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sphbfhyl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gt2hwxbzukg.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2qcedfoxz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzbgzbz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gt2qzkqfoie.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2caxmvuer.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2lsphtdjv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2zjlnzaik.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2cywfwtks.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytfqlwzh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppqawoki.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gt2ipmagxcg.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gt2gqlyuhyk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2dbjprhwe.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2eaulhirf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rklrsltz.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2afkqwrqe.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqvnrgzh.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtfvprsg.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2eopixsgj.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gt2pxwofzld.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gt2uejlyazx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gt2jkubgalu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2lfcchveq.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gt2iomwfsik.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qfegxsqo.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2qmhkrhiu.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2ozezjcyt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doqivcwx.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gt2xvozpnpo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gt2broblmsw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2cfjfyaci.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2welqfsgk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2hgaasyie.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2xplvzifh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gt2thsposjh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2dgvrwkhi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwqgewt.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2stuxrnft.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvcheycy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2pauciekp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2xorbplzm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2enkvohqi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2yoluakkd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gt2yxtasjki.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2tcrtyxja.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2womalpay.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2rszshhrw.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gt2abmfnsul.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vlngajva.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2yigmijpt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gt2abutoljy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmwofeub.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gt2lvgbjnfj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2gcryfzxm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2vvwbbzkv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gt2vfaspapp.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lifsqvkx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2iuaiktil.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gt2hlblyosu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2jyqaxuhz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2kxvzpkvv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2vxofgfqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srcdvnix.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2pevuuxti.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gt2mjphpung.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2kckzncvy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ojbaxnpd.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gt2phwxzaol.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gt2ztijmbqs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2tibrfvjt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2xshkdukh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2whrsqccs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2nvbxnvfs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gt2juutumlw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2anuuhehi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2iqkqkfye.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gt2yuuqqqdp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2ohmqbvsx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gt2yhdxlsav.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gt2olneujud.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjkhitdh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2blxzkvap.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2bkhnxaeu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gt2pkwyrsys.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2cnfjjvld.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gt2msuibqiq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2usewjbwa.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2knvzfzsv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqgyjzli.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xcyztnsb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2mmeeqgej.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gt2cefknxth.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ybxpbeiz.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2iyeuvfpq.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gt2buyzudbd.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzqdvjvw.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2inkmlzkb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2urwmovgq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2saxzohub.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2lqamdjch.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2vqzdopzd.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2focmajld.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2wimchbxh.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2nzvtuauz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2aaqbrrpw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2negdjasd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2ryiliwvb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2jrrspthz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2buwrswoz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gt2skfdyjuk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gt2qqllyqik.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqwebucj.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gt2eywcuytg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvloxfl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cyiwymow.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2nhwvdkhl.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2yevfxxlj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2kcbkimqc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gt2ucrgjimr.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2iqhdfmde.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2gmofzllx.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2sauyqeui.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2iaiwannu.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2ebqhojgv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gt2kurtgibf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2rltrcbyk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2gfegzozh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gt2bjddhnzi.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2qepfvkyw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gt2fjiljuhl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gt2vdwylujf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ompdjssq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gt2hmcwdnhl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2blzzsffe.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zwluzyzn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gt2hxkviclu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2xsoiwyje.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2amhxjayx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2jfflskgb.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2axrugcoa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qumdgcno.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2iikepqcj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2rutdicvf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qenvxyyu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2oeudgdze.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2ylmnehix.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ophlbdqm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gt2lmdtigbd.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chqlzpyi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvetlrqs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2qzikclzh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gt2btygidml.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2zlyuzhjw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2dlhezagt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2uqaqcpgj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gt2htxboivq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2dmorbyqg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ixiuhzvv.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2urqosame.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxvlbksw.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2xndngzpk.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2ntdxxlzr.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2zlibonsr.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2akfqgjnl.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gt2qyxvjvge.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2nzdywkmd.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gt2oczizjiw.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gt2oggivykp.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2dhjewsyq.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgqkfrhu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2qyzifqyo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2lkgyjpsq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2iwxjsotx.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wxnkofjp.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2paokwssn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2qbkvxtdq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmeweqkm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsobmlnh.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gt2pkmdnsjf.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2nxcpvvqf.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gt2kprgibrc.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2mphqfxco.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gt2ltbgqcfq.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2ebmmpulf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gt2sjthhscl.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2ckxyqssr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2pljlcgsy.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2qdwadcht.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2xqhiktfz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2pbuqirqs.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmatpuyl.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2efgaevqi.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2fmmurgfh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvrhgcvv.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abswnxlj.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2jbytjleh.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gt2hvftipsa.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gt2krzunhzw.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2madslrqq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xypnuurx.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgfcomny.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2pwfoqqou.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gt2zcfuaeua.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2cdbzterk.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2wnncgacx.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gt2gjismzzk.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gt2mmauwhoy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2tefjycys.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2mhuodcnm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2enkedysq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rnhzkisc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2ftoqcqnr.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2fpqohswj.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2bllqpgyn.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2cgnrddao.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldbrckur.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gt2agglonpz.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2cqhmpgjc.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpafctsc.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2viimgauv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gt2wdvwqlmc.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gt2tneqguhb.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnzbykoh.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gt2dpuonrli.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2znssohdu.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2idwukyvi.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2eorapyux.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gt2yhnjqfat.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2qmecfsen.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gt2vxsvrdds.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvzcpdei.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gt2ikdalord.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2vbnziias.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gt2myqhxgoq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2koropabl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gt2sokotbwa.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gt2ljmzwrya.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kvhslxaf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2otsttbnz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2ooltvbzu.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owfkvpkp.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2nvzxvfmg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2qmyfmmyf.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2gqlwnhsy.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gt2yqkydheg.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2wqufesmd.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gt2hcuudmkv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gt2oftezgho.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2uzzhlpha.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gt2vsxpgown.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2jdtlwdbe.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gt2jfhnptuz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ebhmnkoy.html


<!-- 参考信息 -->