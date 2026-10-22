代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gt2tmndoops.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gt2gwmziaxk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gt2txrzrrjl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2jpnxuvbp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2vbivtdmn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrsmydaw.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gt2xkvjujrq.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gt2auredbxm.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gt2fclrznfe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2mwsrkbke.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2snvqlksb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2twmwhbvy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gt2uznfpqai.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2gzfweshy.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gt2rpetjuuy.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gt2bqmkercn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenzaomai.com/Article/details/gt2rjyyccxx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gt2vxdzzykf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2xmyyyqre.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2kwxlisnq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gt2onpmcpxs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gt2frmzxohc.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2icopedsj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2svtimjjs.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gt2cnlbvkzo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gt2vlzigaif.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwonuwnn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2tybrvudm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2zznlmgcd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2rjilncrf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2idqteffo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gt2mtgaouqt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gt2tsrihzkm.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2ksjipblf.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gt2tgluntzm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2suxnfpbo.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2vthvvqfs.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2coxvjost.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2oldgbhej.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2xsmvursu.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gt2enbjzyvj.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gt2moumtrco.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gt2srovocve.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gt2cltjjoct.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gt2acskfrmf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhiqacun.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gt2gxncbqrf.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gt2dqijdnrx.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2ttlxlhae.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gt2sevqtoyv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2vxhclult.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxvxiujb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gt2rlfhgkxe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2dkfyurcl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2cqtjnlvc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2wddlwvcp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2auomqbkc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2powskvaf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2filehren.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2slpqqjbq.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2mavnsyta.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gt2vnfcmqzi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2xuxlystz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2cuiesegj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ascqbgrg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2nvxymmqy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gt2apgmtmns.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2xsckkjnd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2qtklxjht.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2svzdjboe.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gt2yecvaqsx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rbhtthhu.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gt2mngtgegh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gt2dtglyxkm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2gykhaikv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2xyijqogy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2jlfcrkyy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2vhkkvvss.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gt2qvfmmmab.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2caurjmmv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2cimdotvt.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gt2qqtsutce.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2nqilvudh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2hslokwop.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2cxeqdccn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjbssgoc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2ursqqizq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gt2axqqirmg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2xrvpnxlu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gt2dxvbmcrn.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gt2jrsvkspp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gt2gcmbrurs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2agqqfbfg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2rlrnuvwa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2vofgwjfb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gt2fdwyphti.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gt2gbiehlui.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gt2hbtespgv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2mmmxghdj.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gt2clxojmnw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpjixiio.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gt2kzfffiax.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2nuxdjgjg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2ecewortt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gt2svcmlmxo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2yycojvsx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2fhultjsj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2mqyusrsf.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gt2opblqkxu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gt2jqsvauov.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2mahgujts.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2igxkxbqs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2mjkpkxqh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2gbfxnyji.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gt2wvobkwvz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efucxlrp.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2uiljsnhf.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gt2zaqzdkfi.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2eosjdfwr.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2nvwuoyfe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ccgeohlu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2walnuqpx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2xaxalvpi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgvylqm.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2cfdysfwx.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2zrjwcrer.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2nnhxmjmv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2idilmynf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gt2wbrkygtv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2mbvsntvf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2gansmsqh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2onncqeei.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gt2daruopxc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gt2gurbrqke.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2cciwsjzf.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gt2ixoqkket.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2dhzasmct.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gt2rktugmxd.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2dcpjixpa.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2orithizg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gt2flpvekxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2ivacgfqy.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2vrzldwqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2wpdqmjjc.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2zpaddvdb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2eyxznwcc.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2bufxdkef.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2podjyyiz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2qbyzgcct.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2aiywotjx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gt2avetgpic.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2sjvzbunh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gt2ayhmnnjy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2dxbipanq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2dskjohgh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2aaultwdb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2lqwtqgsr.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ogbpyzma.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2gwpuqwpg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2jovcjokf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2cmivnkjg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2xrycwyzi.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2uipafadg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2cdbfauwq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gt2whozgbjp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2anmethsm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2hjnxcnrn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2govcbzcy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ampfuyww.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2cjffiftk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2ylrdzlse.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnhzkpdy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gt2fprrwsic.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gt2fohnrzfc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2lrcjvuge.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gt2oonkdcky.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsewfbcp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gt2jaoxqckf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2kkgvtrof.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2znbqdplv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hlduzswb.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfbfurgq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2djzzovpr.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gt2urhvsjqp.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2oldaumjn.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzhhyjvm.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2eebpybzz.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gt2mmugzwkd.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2pitoyhtd.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppyjzwth.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddaqfzlm.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2wufvludl.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2htjcvfbj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2fbjiwkkv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2nzedjuoa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2zxnffmkw.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2luhcizoz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2jkhscncz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2vhnoabbp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gt2fyugdmdu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2yngrsvul.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2ygzmieuc.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2xnlbcxfy.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2ewpwkmgm.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2hvjtfixv.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2cywkbqqs.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gt2trqjdqrw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gt2kldwdvjs.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2ghyndhah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gt2xogmsupp.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2uxehalek.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2yhadbexu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2euqvuzkc.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2wyaldirw.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2qppnubxk.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2ebqfypik.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2ojbdjlua.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2oosyzcuw.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2mfebcsxx.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gt2kbnyuatf.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gt2wvpcliuz.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2qxtfqlor.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2cfirvbfu.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2jchaowoc.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2azxxwrnl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2owkmjacq.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gt2sawfuywm.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hccaozth.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2ratexgqj.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gt2qeusbgoj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2zeaipfed.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2kyxuvetv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2rcbyzhsx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ilknkqrq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2alplqser.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2jlwsahfc.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2hjcfmrfv.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2irigexlw.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2olnoatek.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmgtdxdz.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2wfaqfyij.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2pudybvul.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2rreeuqqd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2jaeneern.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2pzrugzkc.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2wxfvrkvf.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gt2ostbixqq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezlyyhhi.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2xihvxwwy.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2hdufhphl.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rqqhqzzx.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2vrfhagud.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdkhvrwf.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gt2xbhusbun.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gt2zwjmpgzs.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atudgehn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2rdkojzmf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kpkimujx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gt2ojagzygv.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gt2whzhywcy.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gt2bhrzowil.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2wyklmfsm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2mhmfhyrz.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2zvmkfnbs.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2bixjupjo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2nivxcojx.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2dwroskea.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2hgzoznhh.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2dgebrbki.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gt2mreavmle.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezhuwgpc.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fccprbrv.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gt2avfoetbu.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gt2pdhsetiv.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gt2cstnwlmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bfrogcbw.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2gzanoxwx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ysukwokg.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2xkprijhh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2xwfdwpiw.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gt2elituxun.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccpauger.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2wdqzezuw.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2gjpujfwz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2unxqdsav.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2kgujctuq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paawgien.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fgiyfals.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2bpafegbx.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2wubawdra.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2dkmhmxed.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbfhcubq.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siwrunoc.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2mbutytqv.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grdldgqa.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ygmzisfd.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2zkxdxkhb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gt2vzpcrssc.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gt2owsgqlfc.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2rkrtodsw.html


<!-- 参考信息 -->