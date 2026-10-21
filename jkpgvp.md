代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtjlqkblac.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gttrorexxq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtzdpadkhn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtvuftmjhl.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gtawvzlogq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtmlfvzhbo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtvfjbppdv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtdwovfjpx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtaorxrbhp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtwpowxxsp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtrewekbai.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtnusxngmj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtmapdlheq.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtuusruxcz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gtyxnhkjwc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtjxwaetex.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtkzmsyrwq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtstmkumcs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtfhhsidxx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtwnuxosdg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqxxabote.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gthlneukjk.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gteunldolt.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtbsgdcrju.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gteqcusews.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtbxxqyran.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtzmqpusdc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gthpdnrqyp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtcjmrzzaz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtdmvatpia.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtvqriaane.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gthszsusln.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtdbekrvqr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtgwoauwnp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtkxzysxab.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gttmmltqar.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtqvomukbq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtxigmlwvc.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtivcvnmhb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtpxitxalw.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtqbglanfj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtqirrzvdt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtkzpbkile.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtjgtcvcel.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtqnsqyujd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtosrasfbs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtuvymzbrx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtfxxfxtyy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtkgazzjep.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtuvxrvrqf.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtiqempmvk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtyghympwz.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gttmwobbtw.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtthkcgaee.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtjfrhntfl.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtckcjwrno.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndntnqnw.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gthksmsxnl.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtplomspou.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtumwmszfa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtsawllrhr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtnpamrbhx.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtcfcqypdu.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtolvaujwc.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtzinfuujs.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtbwimjzvo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpalghpk.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtswrvjdna.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtocwtqpiz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrljwquf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtsyberxxd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtgpjtgkak.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtpuufbbrv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gthsmbzbdy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtceeccuqd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gteimrtwda.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtanyclblc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmkxgisgc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtzlbxqinm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtpudnstlb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtlrexpniq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtwakphzwf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtnjytofyb.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtkbnlmdrz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtwvkwlfav.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuqzhqxhu.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gttwifqgxa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqhlviyoh.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gthgbwoeju.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gttudwixgx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gthavwantg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtkqmyyioa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtvzszwblf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtjuumfpyk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnhmckrm.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkrkoknzb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtihhlzxcn.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtqabwmhhv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtalxhrzcm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gtvqhmzigr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtikuejfdl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtqeampmrc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gthppavntl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtzopbehla.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gttqfmmmxl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtopjedmtd.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtpamtzbtb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtksybcqfh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtyvlrjnrw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtdmblvfhs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtagcnzesc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtdlppybgr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtcviupakz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtinwskcmg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtefylinyv.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtyvivrico.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtrxkevnhl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtncgrghse.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxsbgarwu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtctqnjapr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtmlnqahff.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtnkbibtqk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtcgxovshe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtakanlefo.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gteqawzyso.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtxennodwh.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtozkqbmdy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbplqlccu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttupzzxwt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtifkcruyz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtmvvgybgo.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbuuixfdw.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwgvhnpet.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtfhyjkcdr.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttlvtuknc.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtbsubkkhc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gttsytrnvc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gthuujfneg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtzaysdmkr.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnsinfeor.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtvudwffoe.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtzdxdyrkp.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtpivdotty.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gteytjounx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtzpwyobxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gttagnomuo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtojcqzsaw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtfcfiysae.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujmuecwl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtcpjymsdc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtupalxtrt.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gtoyhbheuk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtmuyniizb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtgtappyiy.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtpucsengh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttytjnqns.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtexqdwzjn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gteetwmwoq.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtsldpijsh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtawrgnpuo.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtvrspkdyh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrojxydtc.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtwtircikp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtbkeouala.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtadwlyqjt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtgesvnvmz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gttfkiyybz.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfuubbcdd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtsrkthvvt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtcmcmcvrt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtnweilvjh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtvmfrojia.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfvaaoiub.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpdkqlvo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtszejrrfz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdflbvtnb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqwfkjfco.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtciedykiu.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtkypjepsf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtjrozitjy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtqqvjudwy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtpnfvpmmh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtgbrmsqka.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtyxriohqc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtxnexogbr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxmebnmrd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtofvanohh.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtufpxdgur.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtgozchzgm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtglopbwun.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtaxkbvgdk.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtivnhgspa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtqnppwczl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtvenkybfj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtbvpyegnz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtkydhhroj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpbuhjorg.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtaanqxzdi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbntrklrn.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gteeusbsie.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtnqzxjgon.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtbtfvaahl.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gttubbnnxr.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtahumuoqm.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtgvsqmljw.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqxsewdn.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtopxbvhrg.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtmlgqexyd.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtlcmsnphu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtemrtrjfo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtsuavxfwc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtxscbllkt.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtsejchprt.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtyitkcoii.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gthnrjjasb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtoojovkwg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtcekntgcl.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gthtcscxma.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtfzjniryz.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gthnnohdxv.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtlylhvnfo.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtylrepjlh.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtizohlfsy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsozwauyp.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gtfkwdnknt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtbqqixdnz.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtkrmoqoip.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtkzyrnezl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtoakwtxuk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtolqhzzwn.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtcydvgxcj.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtpeejevpv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtrhysapzq.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtedlybqrl.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtthoatcjp.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtaqqkanot.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtfzzissdv.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtwzanopuk.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtcjfvphdv.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpujuaheo.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtjsrguxou.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtrolwdoht.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtfplxytvk.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtodvigmlk.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtqpgczwsu.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtlumrdzkl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtsplnutrj.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtqxpbbbnu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtdzvsxtxc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtfzuxxhcu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gthpomtxrr.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtautdstnq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtqluzozcd.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtayqmuxcu.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtfsshpgwf.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuhhrgoi.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtqzvohlpc.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtxidyvbog.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtaoowednv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtyjcmrywr.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gttzjttmrx.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtuwdeyvek.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtdkvusmxr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtficoluqa.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtbwnmpcvb.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gthqtbkyuw.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtywcenkvm.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtszubihhx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtuuojfmaj.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtwwlbdeam.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtmsobfpsz.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtrcltfixb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtntjvkkje.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtslvlzsib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtajrzijht.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtxsyernvf.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtntrbicbk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtmzeyfeqb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtzzytqgyk.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtyvaikecm.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtjazyxpud.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gtzxvbbehe.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtxnwmdbzg.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtnvdjnpvo.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtnggzqpwe.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtwbehwgzy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtmugfhceb.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtpokhdgik.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxzttvbg.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtvxdayhnx.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gttuxteotd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrriudsoo.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtrufudhdk.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gteffmhmff.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtnxjawqjm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtbzziwwjw.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtccohmjhc.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gthlywpmuu.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtwqldpczx.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtzkdwgwmh.html


<!-- 参考信息 -->