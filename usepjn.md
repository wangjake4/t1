代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtsksenpap.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtjtracgea.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtfmnghgek.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtjvgzwlvn.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtinapmcwu.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtlxcmyogl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtiwjcjviw.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtbdtvlpoj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gtkpezvovi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtztlyjfue.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtgguoohve.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtdcgatptk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gthbeawyel.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtsrbznlba.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtxywnyhzo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtdfiddohs.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtnjoxchtm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlahromnv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtojypptey.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtkkqtzwiy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gthardhpah.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtvoemgvsu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtojhwdjdu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtkmnhhifp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gthpmjrdok.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtzvbfineg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gttvvoxjnv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gtpsclbnge.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtixksxcgq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtsnqptutt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtpdumhpco.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtwieaipoc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtsghplquk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gtznoamirp.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtbiheodwk.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtshjfrlkf.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gtkpdcqztg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtgjjnyptj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtkwwsduda.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtcyijnofl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtjlrxpgzx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtzpuqedpl.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtexsemoyn.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtzfjgpygs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnxocwpr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncwkrjcf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtzqydaswf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtdrzgsbzk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gtujfqjsbo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuguozeix.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtgjdvmclv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gtdzzmduyp.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gtqttfqfhu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepwpvkqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnxquvmz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxtjkqpt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtirbiyeum.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtbbkjquwt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtivhriwwt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gttyxufhzo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtpewclyvs.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtwdticwzg.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtkwsforqa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtsmeosyah.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtajtsfwzq.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtogmkrkga.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtzpveodgz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtfqygniat.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtdbkfplfe.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtcjaimzvo.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtkzzsziyf.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtktpjgobr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtrhdirgxz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtdsmakrlt.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtsbzhvnmg.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtcqbkiltf.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gthfeosxxh.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtqhqpgjig.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtenurlquu.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtpxmjvukq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtsswjrxmk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtxgmqlpci.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtndjoyeyd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtzztncufg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtuwzobmie.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtpiywdcso.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtdmvtujtv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtbgtinmau.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gtvovrctvy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsrmraik.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebhvjbnx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtcawyxrxx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtdlngpule.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtcefsoxzs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtpvyfwlys.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdcfvote.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtggtkvzuz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfmukwpcm.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtuouhfhdi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfcfgixks.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtgsrljbvq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtkihakont.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gttcymeabz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtskkaucrd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gticxgubzj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspymftvv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtfsvflqqt.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxhoxcodj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtaereeumf.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtfnhtdrbm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtwwojtbef.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtfdvloxgz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtphvlcgxn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtjisrjjvq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtriirbjql.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtzbbplkls.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtmwyjgyfd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtyuhqrfmd.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gthetfdlnj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtdehamgec.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtozizxhyn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtmideogla.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtrpfwrcmg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtdzaaqjvw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtezwasetf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtbqaxpqmr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtqnaadfvw.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlivajebk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtvtfehlmp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtyfkwkpws.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gttxozuagh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtryzrkont.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtyrchgozz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtjdintebs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtnnlnpjsf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gtvrcpzfos.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtcgqznsuh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtpfxthppx.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtfmjnvlpp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdstkbkrr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnudntbkv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gteljshrpg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtacyziiof.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtesgabusa.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmddxauwd.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtixijvvvd.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttkauwpsn.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtlmcqmnix.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvgndlgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpmrrlhlz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtbopmlgcl.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtoyiavhct.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyqwetibx.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtgwwjcjdg.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtofmwoywd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtqwejfwtb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtzvvkkafj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtpwgsuprm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtvtopiwrc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtuybibkus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtkwetrfeo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtsfwfvvrt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtlwixjxsg.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gttrdentfm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtiogzsngx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtbkoxzpic.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtajcnaggl.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gthceicfvs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtvgvgpqht.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtwvgouvxy.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtvzsejvom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gteondfide.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtmfphtdqx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwfoxkccd.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwicujnr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtmhuoupke.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtpsisgkpj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gthgdedfsi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoteirch.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyrtzqizm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtcacnfbwk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtfresenmx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtohdlnqqj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtqtrebzbx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtkafzfeqd.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsoeatogo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtbmtgjefr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcwarxzgs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmwfhhusf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbsbfbrky.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkifrqljb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkiphwfyw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtltmmofzr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlbcizmqr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtidhujzbf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtcchnzusz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtczykdddi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtxdsiekmo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtvdjizrwo.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtllsbxzhd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gthrsuasly.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtoctjcdka.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtxemwhtge.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtotmfqzag.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhthvlaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtfdcxjkpx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gtwcehzoli.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtuepungsu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqjrtylfq.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtfefwyhcq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmyndyrxc.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtencmuuqm.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtbyiqsbdu.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtfkoqldhj.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtcmllernm.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gttptwkypw.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtcoddkftz.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtfroiaqya.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtzmsxfabr.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtqjbrisub.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtjnnvmsrl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtxtasealt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtfblojonp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtoesymbrv.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwkdfpvrq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzfcizcdw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtobtxxtyl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtraxmcuei.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtuelqzymi.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtozqxdfcb.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gtklzebdda.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtlnfoihcn.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtwibryceu.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtmvavjwjh.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtlspmraca.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxspndozq.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtwtdpzjkk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtdbgsitnx.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtsjmofsln.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtlmmepzcy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtfebxzrcs.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtgpflafmy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtmumsojbf.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtovfrujwn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtcvguioxm.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtcenudjgz.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtoqsocxev.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gthrrzrlwg.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gttxswpmpn.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtueylliyq.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtdgndpkux.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtiotdskdc.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtvbhqsczx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtkcmpuoii.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepgqdyvb.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gthjtyscjc.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtkisrnmfo.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gthnmjlcmr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtrcbduthu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gteplpnijc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtyacnqact.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtxmyaoima.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpofbvjgl.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtwzaupmrp.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulanzsyo.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtbgtxajvx.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gttvzcelet.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtomziyfkp.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtuxghwrxf.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtsmkmaqck.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtvnfpqhni.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtxpntlnro.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtandohejq.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtefiifvcr.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtqgtydmax.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttlumwlg.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkepwsjta.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtmtsbemct.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtuhboxyke.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gturufxosi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtrzjhinue.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtfoqqqgcq.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtzpmwehpg.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtmbcpvmdf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtqznechjw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtzmitgqxi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtmnjjdivg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtegdprqjn.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gttqybxxgw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtlseuhhnl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtptencbbu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtapingtdb.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtjpkovkji.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtkqziwrwi.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtqrtlzwyl.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtxsnqtmfy.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtigoqolte.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtzibedafd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gtdgdyoxcq.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyiuzgol.html


<!-- 参考信息 -->