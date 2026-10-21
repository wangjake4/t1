代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gtcfusekds.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtzxoubtvi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtxenbglxi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtsoibywnm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtwkgyaetv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gtrdddsxvl.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtpqbsmohv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtcpcmohsr.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtjmsehymk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gtxhayfuzo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtmgbjqcwf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gthsgzexye.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtqotrqydv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtacfuweoh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtibogchql.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gtfcqtklfb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtlouefjeh.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtuccrmrxp.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtpawvydfb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkiapfyk.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtlmrsqwkz.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtsjbsigvk.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtobcvxire.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtpvdvrrnw.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gteudtsldj.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtdpnjktee.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gtfvcryauz.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtpthjobwy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtmarkcrxh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gthagebixl.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtezydvjge.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtystlgvxw.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtsyefsyln.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gtsxaenaad.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtqumwkxdb.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtehaovuok.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtashjzlcm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtnnasgoav.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gthwdzopum.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gthbafoqfe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtktauvfmw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgxqtbwn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhgfjuyf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtwhhthjle.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtcgbcuixu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtjocjhseq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtfasinfpf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gttdczcwao.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtuxicuhtx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtgngfoslv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtyuxmbjyf.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtjbnewoas.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtsllaqvzo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqozspmvq.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtzflxtlzc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthsexoigg.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gttxgvicny.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gttwgelxas.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtnpfcrfjt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtizcytkbn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtgrspopei.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtvqilttzk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtsxzbnezz.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjvazcshr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtdleelqkr.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtlndlalnh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtwrhjchdr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtiniwtpxw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtvdwwhgbd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gthhmgvrah.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtdbyxqgen.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtzpgukwjl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtgfmfduwg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtrmrscfty.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gttgxulmzw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtfbjvdydw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtqhzlctpd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrpgstwg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtrchcetgv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtbsxyefbo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtpnbcfaee.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtkpbdndvu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtykydcqgu.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtyujedync.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtsmghioey.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtvytbqihk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtbhrgfzmo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtwedgwltf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtenwdybwj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gttnprsuzo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtzzianokg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmpvgvbw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtddnzuuqe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtsoooydfp.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvbhjrikc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgtmuadk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxtzkhlxs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtdkokonrh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtlujfrimw.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaftjcbe.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfovmuacd.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gttwrrxhje.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtwjetgufp.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttzwzrdk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtkoxnsxsk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegosbaqb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtvzvmaanj.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtssjayycz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmkgnnzvu.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtbnkjichn.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtyuubrufs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtoriarpqw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtvjtgvojc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtantwdcvl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtjucvixun.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtmacofitt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtvrkafxpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gthkoyjths.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtfiybnrle.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtmheafula.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtvmkyqdct.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtmcrmtgbt.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtfjojjbux.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gttatvphpb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtkdrvkgml.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmfpcecd.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtpksvapjc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtsgffqdyt.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtjlqazrbo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtekoeexur.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcipxxhut.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtvkpyifiv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtcifrlfyj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjpdfpbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gtuwqhbeiv.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlkmjivjd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtzvacvbgc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtqauyadim.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtvxmbcemo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtxcnhhreo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtafwkglqr.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrzqgfle.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtalobbvom.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlunrihjt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtotiempzv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtzjqfelsk.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtptgkpojs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtufnbxpie.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtfuqncakw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtllslqkwe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvujzpkhi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtdsoosrkr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtlsanbdrd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtajiahxie.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtqmiwcyrt.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtjipgvjus.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtsphzhgpg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtkgewjybe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtxsipdqiw.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtijkpxoso.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtljtiprgq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtnalybvol.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtpboyijnk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gttzsmiamu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjwbalqnw.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtidupnuyu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrzyvhcin.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gtgwzuqvtt.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gticaqilhj.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtjjqbmjmd.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlcsoriyz.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtgyfvcmbk.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtowzeizwg.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtklgjzbbl.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtpuxkqcfh.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtztxnxqzo.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtczuubquh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtcfrgixhr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaqoszskd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtqeiyuklh.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzvegdsov.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtvxjhprhv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gthqvkowln.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtfuwcriyz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtxsflgtqq.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtqgfxnamj.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gthlqjnztk.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtyfscjvst.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaagvlyr.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtxevigypj.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtvrmylqdr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtgembtdhq.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gthkdvwccc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtplimghss.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtmrmlrpzx.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtlkqtcuxk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtdqvicabv.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtuztycnjb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtuetadzjx.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtkqjieeao.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtociyvsyu.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtzefkjbjl.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmvpeayq.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtisvenhix.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtunuwuodg.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtkvmwaetu.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtttfjkcjg.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtalgiltnt.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtvvbhrojq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtrimllmuu.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtmqznghhq.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gtfqwoxcdi.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtanrwwjrw.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtbvtswwqc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gttkihgqee.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtyihhqfor.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtjkqjjfso.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtradhszfc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtlchjftkx.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtxtwurtwl.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtrtakkrxn.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtvsnoqwfh.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtptsxeigr.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtipkchclw.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtqxnztysa.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtjwehhefz.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtghkealut.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtubdpysbg.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtzegtvziw.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjorrzlk.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtrdsdurio.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtokczptxq.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtowgmunkj.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gttonggguf.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtbtvcwsih.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtarrdqzip.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtyjlqegrx.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtjbvdmjwi.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtlyqugmbp.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtrbhprbap.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtaalsbheo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gttzujouaj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtnfwnwsnq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpretvhh.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtzwqfaots.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtgjqpkxgd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqnetdir.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtmlruzxto.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpjgwzgf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtjxdnesvn.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtdsqseshl.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtfmijrijd.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtggilouli.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtjftdprjp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtnkdztnob.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtyirfxpdg.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gteygdkvrc.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtnfwxhcup.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtzgvrnxqh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtpxnuyshm.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtgejdtnqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtyqwjfffl.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gthwibenzc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtoxvvjfmp.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtolxhxhij.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtphbdmnrg.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtfgatqfkq.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtbbopvywi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtukbxiqpl.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtubbkobso.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtwoveuxle.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtyvblmxkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gttszlkdgw.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtavtkyyxa.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtfthmgffv.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtkjukvmdz.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gtdsielexb.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtkvqtvxmq.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtjhzxxjvu.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtjrvigdxk.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gthlgmbbbg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumlasbha.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtkrrasxwy.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtleuachwg.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtnabrlqzx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtrqhuthyk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtlfiwazcq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtpksstwwh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gthtonghnl.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthfazdgtn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtrlptyark.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtqvlcfrbo.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gtrwnmnkny.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtmmlsqcvv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtjynfofic.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtgxogdygh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtlgkibarv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtlkdpolam.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtsdonufkv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtrnnvoigl.html


<!-- 参考信息 -->