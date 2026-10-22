代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtvyofdtlj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gtrgrfoyqo.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtmehjgujr.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzmaraai.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtmlfvbjbz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtncthtxig.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gttjwwhznh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtutbpoczz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqulmltpx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gtmqkrnafh.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtadhenutx.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaerejvb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gttzfbrbzc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gttbdullsk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtimezbfys.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtmbdgvetf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtbvcjycxd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtkekuxywk.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtfxnjpkqj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtynoehkiu.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtmvsaidad.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtarqndwho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtrgmxpzvk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtyyqxiien.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtxpwshncp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtrfopdfxh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtaddgkskg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gtutleuikt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtgjinazbg.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gtxbtsowkm.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtqzwkcddg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtbenftttn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtaaovxxnj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtbwumkpdc.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtqgsubacn.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gthbevbksh.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtiryvbmuq.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtomttaufh.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gtttztfvax.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtebrbekud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiqbdaoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtadkgcfdr.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtrlsoewut.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gttwpjhcut.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtxnduenbu.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtvhqfnnyr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtwpekuhfr.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtykztdzjf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtcgzhjoxl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtgvoubsgu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gthiunfygu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtbtyhzmvt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtbwfmggbx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gttndzphof.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtujpbezwi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtnwlhgomz.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtufhksyal.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttrkchvwn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtiykomxul.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtuqseybcf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtkgqxgfxv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtlwhhzglt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtapnpbsgn.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsgmmzeh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtomnrpmdw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbwmkryhk.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtmkooqtrj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmecqflrp.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtjgpvusyv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtdwguyvft.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtpswosscf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtzncpesqn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtwgpxyiig.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtmjdmhjmi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtzyrwwczp.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gthgknjdok.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtqfwvjtye.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gthosmimbj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafepzwhl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtpsncluzn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtcalbrchv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtjdgnemlg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomnhbtnm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtxmfhcyad.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtoavzhhfe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gtkvclmwwk.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtkncxwstc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtfygprssw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtkrawvhvv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtrkflowpn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynxsixhd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtjvkxduba.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtcxnbuyds.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtzpyejirz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gteibjhrwr.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtbfrveuyl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtwwddpabk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtvlhyhixc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtoycfbhub.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtmqeievls.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtvactnsbj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtcmjffeej.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtsmvtzdoz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtpegnqglk.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtabhiuglz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gteecqymyr.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gthzjvpsgm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtudjjjxbe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrpkmkpwa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtaaanymlx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtwousnfqj.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlurigvfd.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtxunywinb.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtleprmwdi.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdrkqunxd.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtudlpyfxg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdjoznnbm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlahphuaa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtqcxfvzwy.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmtvrgsrn.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gterhsivwv.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtqsrzhswh.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtkoplxbhj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtpblylkwo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtmbvhlsrv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtmevdbqid.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtrddpfrfr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtytmbobas.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtrtmucexj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gttwpkaifv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtfdwxpljf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gtumjmdaie.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtpwemqywx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtbtoavzmj.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtderlelzs.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtdrzlhdlg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtripwjcti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtbcvalufv.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtkwqbjwxk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtllycrrcs.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtafofrtfd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtunyeeazn.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcnxujfc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtokiunvof.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtlwwdeehm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtajeuxtiq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gttdvgblbc.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtfszdznue.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtnfwzrrah.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtsdcexmhe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtlypymnld.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtknemagtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjkipwhqr.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzyvyqbtk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtvwumqjjh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtntbpkmom.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtesihgsvj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdnyoakjm.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtpuzzudwj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlslnlywl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gtxoxpgygj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtiszkualf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtjuoacluj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtyuqsjhmg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtdmvkpmvu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtagggoooz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtvjxdqlbi.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtvcgimcae.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtbkptnymk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtytxufuyu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujxrsaon.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtrfubbjbn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtjncmbdjm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gttvqtaacr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtjwqdrfpo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtncklkehk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtblefwfwg.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gttqyfyeuk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtesbiekhl.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtaugznbuk.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtwsazddzr.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtnlvooihn.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtpuabjrvr.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtdufnlxka.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqeoebhec.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtorngozki.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtrnccgzol.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtapoxqppe.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtgxvwvaww.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtktmyytfe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtkhezkizj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gteederqff.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwzsgicxd.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtxnlobiqc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtxghkfxgs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtbpjdllba.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtsbwyvhfj.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqkhhzxn.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtvgqwgkun.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtnfqyhewo.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtqyvezhzb.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtnilynrko.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtsazsjvjo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtwjplmdxx.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtiykmeeov.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoycoqcpx.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtewmngxct.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtwozmdvxu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtoczfqrru.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtatowsonr.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmqrcnsyy.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtawdyhezn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtvuhrxthc.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtwhbwwmno.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtqifavone.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtpombfrff.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtnnriehvj.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtryznntzk.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtkbolgjbl.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gttiwuygtl.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtmfssbmgx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtqlcufryg.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtnrecrfob.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtubqwkrwh.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtpfdephyb.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gthkgxeift.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtrjaxkkvy.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyvxkufv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaahmozx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gteohstieh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtraxdaslu.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtpqdmyoez.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtxpqybisu.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtajyhwcua.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtfgtqneoc.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtavcyuntu.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtedqwihrp.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtluvboocl.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtidkodzea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtmbrecolc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gttkcidmti.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtjvlkoxfb.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtycssxxvx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtvulzruro.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacayudic.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtlhoschah.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtqfnhcqyw.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gthzblaccf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtpsdalhtj.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtqlimqzsf.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtawobkbli.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtlfgrpgcq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtvzlhdmlk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtgldhrgoc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtabwlmynn.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtfkfdadrf.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtmffbqbou.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtunworask.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtdotvymmb.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtwmijyjmo.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtfjkberfb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtqiwrbckm.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtacwwpyfj.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtdijfixpw.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtfiqtmqhp.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtxyfnxuhp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtbqpexgmr.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtphwdgsyq.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtwthuuelk.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtfarazjkw.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtfebdxpgb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtethfvpeg.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtahigjxzx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtjduwpjkv.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttuixeunr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtustvatix.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gtfbdagkdm.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtzkxxvbns.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtpfoflydt.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtcjhynkxj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtpdeuywtz.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtehsayxlj.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtgzyadktx.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqpghrhxc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtawgnifrh.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtwmfdramz.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtsfbfppsk.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtocyhifzy.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmxwjdcm.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtszpfzqxs.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtgzhvwqck.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtxrckgtov.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtqfqipcwc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzlotscq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtfugehkcm.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtgjghanos.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtzerqemzu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtkftvomgw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtzzjodmqu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtopaigfiu.html


<!-- 参考信息 -->