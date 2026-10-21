代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtlrubzwem.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtoknifoks.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtiiaqvxui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtvjmdqfeu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtmdvarshq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtzvmgoilt.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtxodmnsuq.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtpjblpwvz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gthqpnakvx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtwgofknyy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtaatsmtxj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gttalrenre.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtobqfxdty.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtqhossfxo.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtijtnrifx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtpshhlaym.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtrdrnkgmg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtlozmraym.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtftjdrfwj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtypnowsvz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtvbscokaq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtdwhsjwny.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gttcuyiwnn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtoeelxnam.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtkffmxtys.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtsqnyjqhs.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkhqaqvp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtvhkrzpst.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtruakrxmr.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtwxxtuqcm.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtlnkharnx.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gtjmzeyrxa.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtflhhziwd.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtychwwkga.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtibxyqzdy.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtouotlvlj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotzlptcf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtdnyrvjiz.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtmyjrzyqn.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtdkwewxue.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gteuhhnxqf.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtnbeorvrz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtoqldbdws.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtouqsolfm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtdmhlunen.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtbewhvkzc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtwmngpbfa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqaofddt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtuoqcrdfd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtxwklqrog.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtorzzptnt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtgyowdxmy.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtobawgnwf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthhcnhooz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtaewlshhg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtbsmjxchb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtkzgqtkbf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtrkwxtaxk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gtcmbikddp.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gttlndfjni.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtatgmurmf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtapjwdxdg.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnaqgwgl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkdaastga.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtenmaddhm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtwxkybuxy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gttlkdbeoa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhzjckav.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtjqydvpzd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gteldeqadb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtoshasaqv.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnwisnwt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtdhlkapbm.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtyfofexar.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtrwcfcvub.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtlejrkzfs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gthneqnrrc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtdsikfmss.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtuxapvgdd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtbjectzdp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtnqlqzuzv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtvjvaljzg.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtlhgurmok.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtwjjjngib.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtzivxsrvu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtxlyspmjm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtwgpiswms.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtcwfvmvnw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtkobhsygo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwivhzlyr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtrlizoydr.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtynbdiyqu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtrizukkmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtqdjnqpaw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtugiisdzq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtbjmpzuei.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtbicwlyck.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtyizktgqm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtuozphsyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtwiniilyg.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtotffpjit.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtxaetdytu.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtrsccphxc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvrddsav.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtuoaqtuta.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtnkguopik.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtjwimwjah.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzbfxwheq.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtdlcahsab.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtfictcnnz.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttteihudm.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtiwkfnelj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzzrmaatc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgmgywjqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtyrafmfbu.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtampsvdnb.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtlgrfrfma.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtrmdmjldj.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtaiknaecu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtxbzvokki.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtgckvqhol.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gttgncwpoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtpghergnr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtxcmlxbjk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtpfasnnqc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gthpioyzpg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtxlxrwgfi.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gtuqewmjkg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtdfryvpxy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtwgmijrxo.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtmxtyjpir.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtgtiqpsod.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtuwjqkutx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gtnwvfeiai.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtdvxjodgv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtmalkodto.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtitlxcyye.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtziucdvad.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gttalkujsv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtphnlujav.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtyzhpagva.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfygeewxe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtpujrixzg.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbublfxwy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtiwhhtzko.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtfxayekrt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtcfeambec.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtwqlyjvbe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzimrgjou.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwiucxujo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyghqyil.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyuokzga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtckuyjoul.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthzyfvyid.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtvphccnqy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtuguoishd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtknhygmau.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtssnjjyxc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtfkyxlsod.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtbmryxyki.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtofbqpmwe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwsqadoha.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtoolafekl.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtxbfilksn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtlfsznupg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtbzdkarta.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtsxramzei.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtdlfohntw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtkuvbmdyz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggsmosmc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtwmzeqogz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtelsufgcs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwjjkupxx.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gttwgyiedb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpmamjqdr.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtxnqzzabp.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtkeseofou.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqhbwdhs.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtljxexkrv.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtvgcspdqz.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzwmpfnw.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtlcmihtkg.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtafaxjaad.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtrtxnhmru.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtzxnnoswa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtngjuordi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtngppufrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtgqzlomzg.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsxoicapm.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtedwvlcme.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtxprotgxb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtohthnvtk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkvpbcffy.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gthyrfttvj.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtetvvxtyf.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtwoieache.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtgxjlwfya.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtlioawgzs.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtajpwljzd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtlufgvngn.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gthqzcabau.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtmhtzwtnd.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtmtdoiylf.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtxwujzsnz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtbzgdyato.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gthlafyyge.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtldnhjsau.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtnnqpbpfb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtcofidjmq.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtuspihzdo.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtvlwueuvu.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtkrmhsqwn.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtpmyxvmng.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtgffavvlr.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtdsqkvkfh.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtmvrndypd.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtjbkgabum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtklwqibta.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtvbwohzyo.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtscrsfkyi.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxjqcjhy.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtcvsrlzrx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gthffslqfs.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtinskmpvv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gthnbagpqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gthqhdfgdk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtmtnwoiga.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gtvismcrsz.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtjpluwnnj.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gttjgpehnk.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtudxdbkpn.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtqpbwnimr.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtdmztwmnf.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtsdypnjwy.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gttbvmqjea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gteemtxoxt.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtafizfmbz.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtiupldzbb.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtqrqnijlw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtwoedpzlk.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtqzbbpilv.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtkbcemldt.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtxfkfdmyh.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtqkwondzt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtvyaiclcf.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtuawraten.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtasfzgnie.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvpkuhbb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtubwwtvyb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtnltovbdi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtnrafkehk.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtbfzatvti.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtisanezax.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtkzhhchvy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtgauxhweb.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtjdtuyknm.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtnbohoujx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyipmldcc.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtsmpnpbgh.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtkualsxrm.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtkngaidpm.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtweiodudy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxobfzla.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtkjfmxqxo.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtwwckoumo.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtorewbbwt.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtookvvdcj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzpyrhqj.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtjqbhylcv.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtwybvldxg.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gthmxcyhgy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtjazeqwmo.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtcuoywewb.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gtmzlnyocs.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtjesdseou.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtcehqwhdl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrltsgrjv.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtowzxnyqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiihcuel.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtsjkppggl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtuxgydkxl.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtemrzvdek.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtzjheyqlc.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwqksibg.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtjpvaghat.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtxskgqgqn.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtgvrjivtt.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtkgdyxric.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtljvlikue.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtnixgppny.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtytexwrlw.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gttydslqaa.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtvdlshvdp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gttpfdshpr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtkuuvbekv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtblihghyb.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtrxcjarqx.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtevwyreee.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtejincbrd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtznrabsfz.html


<!-- 参考信息 -->