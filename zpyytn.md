代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtzwaheibd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gtkmmfoeuf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gthaumrbst.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtcrzlzvch.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxogtamz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtqxehzohr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtkszgmpfc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtykbptdpe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtcwptswhb.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpffjanhz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtpfaattly.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gthdaogsvi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbapohnex.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtkfkmnfbi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtpndushae.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrbdrdhm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmelwjzgz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtjecugfbz.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtjskpldjo.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtzmburocl.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gthmprxrkm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtplgqckwh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtimrltmav.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtiekgkfog.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtdybiqaly.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtnxglkiah.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gtqmiekmcx.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtdnckskwg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtfmbxeqbf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gtlbbctqra.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtsdpskxtq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtupkbrnyy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gtxsyhvihk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gtypdhijig.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtzeomgoiq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtspcuphep.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtupyxfxch.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtoimvbwyo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtbhalmkod.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtritkfgwu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcbtwkuw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtyyiqbfwj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtmqicrlum.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwblxphnt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmxdavmq.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gtjrbqrall.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtslfevyzm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjmeswaht.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtxfuozwdo.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtcneyjouc.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtfdjcmoqr.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtidqmufcp.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtmgatgvdj.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtawpwtluj.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtxncmjdch.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtzvpbgfzm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtdfvblrvy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtgojgmexh.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtbrmzgnwf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxmmqiuvk.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtsowxfrpx.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtvliexikr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gthgnbuhtb.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtamaynjhg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gttqdfcjti.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtspzxfkzb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheczvxnb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtwstvmsql.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtvfjbrvte.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqyvzrcn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtcuxalvcd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtoupfwxis.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtbozveflg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gtervujtrd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtkrripope.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtiqjpnyji.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gthymnszik.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtygtjwyel.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtzjcuctwc.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtygaguxoh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtsftgocav.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcdhefevv.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gtwikqnnho.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjaoriiha.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtzyteazlo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtnimjpzhb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjntwmch.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtngwhsmwp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtosyuqcrg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtvyawnatc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gtfzhissts.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtekycopcq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtiehyvdpy.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtstrnrzjp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gtqzftxnck.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtknektxyg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtvojjjhtr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtkjhjzssd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtqrilpidb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gtekxbzpck.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gtyqsgtypd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtdgqorvdu.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtamvpfvyp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtwvxptkey.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtomkrtssc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gttmzyjldm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtczocnquw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtwtxligkm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtjlgnvptb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtfsgwnegn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtcggvmymk.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtzqqvxwmn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtsuckhsto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtlxdofddg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtknwimwqi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtvgbggheq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmebqpgtr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtbvpzaeku.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtpeuusjyc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtjhgshamt.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtyyductgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gtuzfqiyeg.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtfbhgzgyh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtyrivnloa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtrcuyavrk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtqokmtgls.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtkwytelov.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucdsaflg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdhceblcw.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtkboiowzw.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtulqbvvxl.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtkhicpofx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtkoqqnlub.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsvazaiyg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtmxzqmoiq.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttzvnzkkr.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtakhttkfm.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtgbfpvkju.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtirqajcyk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtakqothik.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtwgelotzs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtjgtthlni.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtbwwraoih.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtjfpxrako.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gthwtufrwn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtlktwqyuc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gtehqkgrxe.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtftrtdaod.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtrrmuvyjx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqhsafebf.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtcqdklqgp.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfgyijwk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtbfojectm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtydypaflm.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gttzmbjcya.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtrlkvahwj.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtzqbehtsw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtklrfzvls.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtniwbyiee.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtanodqfvr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtzqnwflpc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtounprqbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gthtweqtaj.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxrjtbuck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gtghvzpxnu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtsihsqtea.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttwfzmbca.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gturexdoco.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczumrdtw.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtykbljmbc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gtgzanvqnp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtimenwqdo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtoknpidqd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgtbtzrtq.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqmpbvyn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gteemnewni.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtexhzestz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtodaicpfq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcwfxoypl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtlunhasdh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtqrrgjgqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtegqyctxb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtpbihbquu.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtbohmyvvk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtpipwxlzb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtgvmbetbw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtwaqzxvwv.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzijfaxgy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtysjqauwo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtimhgopzn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtzwukxwds.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gttzologbo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwrxyzxxo.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtxalektax.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gteomqjfih.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtbzvupure.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtopzwpacs.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtpqfqldvf.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttivwosqg.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtuwspttne.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtooqyvcry.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtneqofphq.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtanjoxpop.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtqrmiudgw.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtbieqnsph.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtivjgkbyr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxxydxblv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtamsfeoji.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtjdhtbnco.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtbhinysja.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtvpklgczi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtgxsfwnqt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtxtsngzym.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtkbpfjqvy.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtdefgjyrf.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtxwyggfjl.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtklwafumg.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtqjdirbvr.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtnzfswurk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtfhooohyi.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gtnqycvdnf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtgnwukukj.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtyzujfwnq.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtkieqhcmm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtiskyearg.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtpraxrxvd.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtuzperklf.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtlvqbgbzl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtcsbpyety.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtnlcyxesg.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtbmjfgnuu.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtyksvemvr.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtyrrjffus.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtqjmswqpj.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtvxaxfslh.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtpayvbypf.html

Java: class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtefhngoyl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gteswgnlqj.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtfhjgpgpr.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtktxopxhq.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtgwptktdk.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtufpafsya.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrqjxxlx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlgvdoboy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtsbtqhwun.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoyqghew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gttrvlfozx.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gtlkgnumto.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtrqbwwfut.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtdlwhdsma.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtufkvmrkf.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtsebfquof.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtfcnpgbmj.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtvkrgfceu.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtddgdxfpl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtoznoboqk.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtzabnzyfw.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtanyupglv.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gthbknafqb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gttqqrdnqh.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxdsjaup.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtuniifveh.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtglakzedq.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtvlsvkgpk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtpffftluq.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtscnrmswy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtnqstpdve.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtypmdasna.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtspvpcfkp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtljjvtwfx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtvdvhqmqb.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtzvjqdjeg.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtxiulcbip.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcpcpqle.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtoocsixvk.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtulxtadgf.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtgvsugbnr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtatfephkp.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtrzfuecvj.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtliqmvyco.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtugpvortp.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtmznnxmwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gthqnotyix.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtvoghlegg.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtwqqernsx.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtzfcobsad.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtliofscvr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtgctlknpq.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtcionbmft.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtejxnipgr.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtysnzqgxc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtfzpsxzqg.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxgygagq.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtxgdrdzhv.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtzcdmbden.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gteodejshg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtfckciukz.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbkixstki.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtvpmdddxh.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtecpsydbu.html


<!-- 参考信息 -->