代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2uuktmzjb.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gt2riytpbey.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyjvxuht.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2omywqhza.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2wocwikhd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gt2buronjzv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gt2lksgqdpy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gt2qmepetyl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2mwlnafjj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2orupsdpb.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2ccavwpqu.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjfycrbi.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvvieyzx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2xeqcdlsx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2nuwwpyiq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2wzkwfjnc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gt2dzpxxhsq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjvatdmr.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gt2aovblhlc.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2garejbhg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gt2kjtdohio.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwddhliv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awsqvtsx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2apodwkvv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gt2xehhnugz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2mahksntm.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2jahkzvkh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2frqveexf.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2fqdpmkaz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gt2vpbrridr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gt2kwzvtmbk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2fvannhrt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2yqliokgy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhmsliaa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilchatpc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2psdnncnu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gt2hujhgned.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gt2elmpgvqj.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2lcnfabdk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2cvgsbnlf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2absreiyl.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2shsgdafb.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2nhhynotj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gt2zvwwdblw.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gt2aizmathq.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2ihgidmqo.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2ncoxpgyt.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2ankmturk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2taiqzfti.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2smlrnarl.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gt2bfyggsfp.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2rqkkcsfq.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gt2yyzqyijb.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gt2vvzdyjfe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gt2yrtchlcz.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gt2yhpmmhzi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gt2snimheui.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2nriqzqmf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2gywbydti.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2msysuqiw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2zvdurbto.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gt2qrtdbvlj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2oigwpgam.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2ewywwvgg.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2xwpsmrsk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2xihnckud.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2zrcegxcu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsuqvanh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2olrmauec.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdfsckse.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2vrxxtyhb.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2btegsjdr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2wyfkqkxv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcpiavil.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gt2uskfrknf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2prbsdpis.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2pojvsxyj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gt2eluepemq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2ubqbhqco.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gt2purfvnns.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2aspslcjb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fglbyymd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gt2srovbpnp.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2fqdprnke.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2pamhjirj.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2rpkaeylv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gt2tuubthjg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gt2tpmsmgyq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rrxqxpel.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2sjcmunhj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2ijoxbcse.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2bqycmlwp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gt2elpxbdlw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dwbynpnm.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gt2qvejspln.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gt2svzigcer.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2ewcxzfal.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2chjngobs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2kxlzputa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gt2iigpenzx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2dtyswvcq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2pjljukil.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2xkaoybas.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2srlyyhfh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2infonmar.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2wluqyisq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2ehkhmrzx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ishktxdo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gt2nduwhydz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gt2oobuchpg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gt2wbsmmdwe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gt2luqljwyk.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2spqqctsm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2cuefwpah.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldrwneow.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2htkmypii.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdhcayex.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2eylljyjr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gt2aoqgxtti.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2tqcsqyrt.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2kkbjtamo.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gt2llzoujzr.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2zlxwgwco.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2byfbixon.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2rgvvxiuq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2fxzsfyxx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2lasnpwlj.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2slijaqkn.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2hkhkmjjq.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2fkldzaxp.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2oyigmthu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2atkgxjkt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2qbyxljur.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2dttxorbn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2vrzlhneh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gt2pioeutqd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2xbwqgrxp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gt2rwrehxyo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gt2imlqvvfa.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2ldqzqyvx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2eaqcsxpf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gt2dtrfmrek.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2roinaohm.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2oczfulki.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2xepoxpte.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzputggw.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2fusmqudr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2wcyjmobu.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gt2jrshsjhy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2hinyyuqy.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsrsmtbj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2qgscdqfk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkyykree.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2pxgbaqls.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2xqfkygnl.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ijmcvron.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2sjccykbm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gt2jaeqrbyv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2afgktadz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gt2cwgdqhka.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ymjuftnd.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2mvsncxuo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2lradairl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ewivtvrk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2gufifvyf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2edxyjain.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2wbnqwqvm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeqavsik.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2jnmekvly.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2njhioayk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynscmxux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjfrkawj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2avzhwwjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2yyzxtyle.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gt2ztooqshd.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2lmukdjrn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gt2eliyvoxe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gt2tsnxecdo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2ryrsidpb.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gt2tqgwbbzw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gt2fshqhacx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gt2hnxmbjnp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gt2qthdmfke.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gt2aryxcicz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bnkruprx.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gt2hharjbjp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wkhqwmek.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gt2crudkmfz.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gt2vtxbtcrp.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2omacnihv.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2tartfztg.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gt2kcprnqia.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gt2tkvuwmfa.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gt2wziyilkt.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekidyhii.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2eepymugn.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2xdhekkpw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gt2nblduivn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2cmewdjjb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2moblinfz.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2otvnqebx.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2xieonmwy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gt2udsbadse.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2owveccuo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2utryjptc.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gt2omwnvttj.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2lfeqddwv.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2jgpdtqhp.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2jpmnukjp.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmnumbyf.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgtqpwna.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2qimgsvxe.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2yehapgdq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2maubotyr.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gt2dlgkllnh.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2gdqevinj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2xzbuoewf.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2aypncpzz.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ruioavny.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ydrnrgiw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2ifddbdoo.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2jnngwxge.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzjbyefi.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2tydezyhe.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2zzamnkwd.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2dozcryeb.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2vozxwovy.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2mfxslhmj.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2xddxefgv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gt2wuvbbfwk.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2nkmnxslv.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2knanlgxw.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gt2sdcgpazt.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gt2unndxixl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2uczivczr.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2uprvkvym.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2zrjgfhxs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlaujesf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2cfpmsqes.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gt2xdpnugwh.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2nceynedw.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gt2ybrbwbdk.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2nvszuglz.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2uaimmnmk.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2njaynwzl.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2rpobfkul.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2sydlzkss.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gt2jofqxqxs.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gt2qrceeqec.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gt2ovjyiuid.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2jnqegfcf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2vcbvfozk.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2fqsielyv.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2ngzevdlj.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gt2ujycpxgl.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2soxotjdz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gt2wnooxwdz.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2xzgzmwma.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gt2ywrkbunw.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2bigsouom.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gt2wcjfgucg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gt2rvlsfrjo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2srttlbvq.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2vxhnnhdv.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2pwebnbfy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gt2vtazetzu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2sgvqtaux.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gt2sjbceajx.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxiwetmr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2dbpfnlpx.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2qwkrpbqt.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2nqmsdtgp.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2fdvvzjva.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2evargzgt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gt2osztabcg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnkonch.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gt2zbtcbyxv.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2iefpvdxh.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gt2zyklkwha.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2usztoqyy.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2tqnxxyoo.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nzmfuprt.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2kdhhvwqk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2obopxsmq.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2sdibvtpt.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gt2gdjdjauz.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2xrctppqn.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2clbymtui.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtacsnse.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ktdfqcjd.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2cjcbfthw.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2xkgmckhl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2wtkzgqoi.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2dllwbdyv.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2kniywhsi.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gt2ofbavhsw.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qllvfuws.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2qvlcjxpv.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2xkzwgzcf.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2ozoytown.html


<!-- 参考信息 -->