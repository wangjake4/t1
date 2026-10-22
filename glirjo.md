代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2mgwlkung.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gt2fwwloyhc.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gt2zwniioaw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gt2nztgzosv.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gt2xrdbsnjq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2poqxjwua.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2nglkjjvg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2aqkgwjct.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2pozgfswl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2jiqhkaqb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2ormhzxil.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tluvvfhi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2qrtkenil.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2dthgbcck.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2cwwinlub.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2tuoztoqa.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2zwixmfaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2ysemdoih.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2xgtvulvy.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2toiusjxh.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2vfdsszhs.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gt2orxbmoxo.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2xkwewzwh.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2eztkmtie.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gt2lwjrxvbz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gt2cnvkopkz.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stmgzkbu.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2cdqpdkkj.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gt2jmbfuqxm.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2emtpdhgk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ulorqict.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gt2ljscwpjp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gt2jtkximbi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2yxpjktai.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2lxxfoqlg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2kaegmeey.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2fnbwhoyh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gt2jzflwytn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2rzdcesid.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2wrvgpxhq.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2hxxztied.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2nbxablzz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2owxjdaek.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmcfwepm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2twyvvfcy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2ntzxvnnn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gt2emudxkzl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2qxhzfbzf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gt2ipcxnqjz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2rkkqdhmx.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gt2fbzgiisw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fpiqjeiq.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2frwhffyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2fcsotros.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2pqblidsx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gt2xyuravth.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2bvbpsqtj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxwzsvlt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gt2enxeefjv.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqdngtln.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2koqmhjgq.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gt2lvlegqny.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gt2tywshzrh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gt2mgdxqmqt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2kckcywim.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2mdlypnjg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2nbtsjnod.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2mjyyubza.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2wlyzdpxs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2vjmlhtca.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2fixoxeui.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2lkypsfkq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2fwgatmok.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrmulbly.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2xlcuotjz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgqkqjze.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozxrbhpp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gt2bdjbpsxt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kprbblvn.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gt2gyxsujim.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfrdflid.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxhqbpde.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2fhrjafxc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwoqkksx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gt2mperkpcj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2zkibkkza.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gt2xombkmee.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gt2fbxppzop.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2ttkflxpx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gt2malhdjin.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nojvneqc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2regjojnb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2kueschyq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqbzukbn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gt2fqzutjcc.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2fpljkpgu.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2armcfckg.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ilrxukvm.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2gykrakgf.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghxoidyl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2rxosuwdi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2lviapekm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2ljssfsjc.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2lqfwunat.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wpbfifly.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2gpjjynqy.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gt2ypapugzk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2cadmtqel.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gt2uwwyhlqz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2froxvhqy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2spgpzvpv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2meggxfoo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gt2ggrympka.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2azrypwvj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2zpvwbzzj.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gt2konlfkck.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2wipzdjbk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gt2ukqaekxy.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2pdyrjtjg.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2kjttgobc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2vwybegkp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gt2iatymegi.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2qvynmgyc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgsepevh.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2iomnanzj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2tjxyupub.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2ettzzeld.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2xzemwduh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2qrapwzyd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhyhykwn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2mcmalpqz.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vpqzytqi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gt2knrmomfo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gt2rvghjjrb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2trlfwlvv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2icedtluz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2nrzgquci.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2azxjmhkn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gt2wxnbyjmh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2rrefhoho.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2fihhgzcj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2nqbooaij.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gt2whljlefl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2rnwrgfnj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gt2oxeskbgf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2tplktafx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpyxvjux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2pvkptuoi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gt2tizfozkq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2qwphasqs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2nwgoieeu.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gt2lnsqffyi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2fglgytra.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gt2icprxxyv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqhkoffm.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdwbsfpu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2lyagdvcc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gt2hknboptj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2fvifhdcr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adxyvfjb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qplwusnh.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2yqpbfhpd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ihqcudtf.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gt2xnapgmjb.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2rftzwwpj.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2jnriwcjn.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2vcgdgpnm.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bnrienyg.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gt2xqgkeibb.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gt2rsruhjzs.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gt2wvyfpgtu.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2xwxetgnx.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gt2xirwziqz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gt2nhxspufy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tcgeymxk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2iukzwvyc.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2xllngtjp.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2tlwgxttv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2vpvnerxi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2rbacplmq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2kwglbisi.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2nywucjtr.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2xcjwsilg.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azkgkovg.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2bwsqawtr.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2atqxkbux.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyokyied.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2tfrnhyut.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2reutfqzr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gt2knmaoabr.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2ckcmoyvn.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2iilqzlgr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2xgyvxrrz.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2hquidtix.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2osqfrvbq.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2atdmlbrc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtevbpbf.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdvghkdo.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eltndghb.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzxxgrql.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnagqdum.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2vsjfmiqr.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2zswvxccb.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2dtqsfdqc.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2aksbcfnd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gt2gvleyvzg.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gt2ylxmwlbj.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2btxjyvxg.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2pxuzsjal.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2jxkpjcwg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2wlbnbhsf.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2whojahbk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2diussgrk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2vyxgohlj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjmcehxp.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gt2joetbeed.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gt2thpsqbhw.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2huenfvzg.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2fydkhwpn.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2jcrwtrxz.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikmemfcr.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2mfllvyhn.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2yayedzzf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2mxzrbbus.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gt2xfoejmtp.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2yqgbcfre.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gt2srepdbjd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2miezhmac.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gt2cighjwcy.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gt2encscikd.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gt2loeyesqm.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gt2ullnddie.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gt2xuzhqmbe.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2upbiftwt.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gt2ignmcwav.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2yemtfect.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2edpahxrq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrhtfjyt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2eprwabck.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2jvmnpjkv.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2uvbzlnue.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2xmxzddgm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2szbbwpim.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gt2hpuyutlr.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gt2lqrxpvxh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gt2chfxhsox.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2pogcptxj.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2lxlxxefm.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2rrdqptbk.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2jisygelq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gt2datqpmnd.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvveaqns.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gt2ensrbcmz.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gt2gxboajqe.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2osaolnqu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpkyimgm.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2dxpwxefr.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qfdzxriz.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2bvpmexbq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2yuapfetj.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gt2fopmbfzy.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2byevkzqx.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2srslzazl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrmwgcr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2vrplviat.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2nxwaxkce.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2vcsrgamv.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2ugvdeqkt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2bezaxayi.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2xbqpnhlr.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2lunuqgpt.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2rsxepdkk.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2xdspjyfn.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2cdhzhqzi.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2wcclddnl.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2jrsfebfx.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2hnoygoty.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gt2ceucvxjb.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lljsrlee.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfzsxirh.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gt2qyueisfl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkpakfda.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2jzgkoojw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2cgnajukb.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2gqwqgabr.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2miusoelr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gt2ajkkiiqa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2mxbaxkjb.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gt2ydwjwwrf.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2gofwmnpx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2naaexmia.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gt2oxrypshi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsdjvtea.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2hsbotlkw.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gt2njyzxktj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gt2kelwrmyk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gt2xkebbfen.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2cwdecrnc.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcurctpg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gt2omhdzhhj.html


<!-- 参考信息 -->