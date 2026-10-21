代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtfaubmsag.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gthzyzmpum.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtpcexiivi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtgibztsvq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtbktpkseo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtjbmvnmnu.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtergdquzq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtkpuyorvd.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtckkdhkbt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtomdtktks.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtkawipyby.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtthtjfpjh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtlviozudl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtmodaoygm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtjmhndolu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtonygyuek.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtjqhmrcbi.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtptqvnhsx.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiriqpaw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtzjdmacrz.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtnqmgztzr.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtbijactoc.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtwpwdvohw.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtxkurhoww.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gthmbnecrf.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gthyryycvd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtkmvzopma.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gteeocxmse.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtjdvjnkld.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtydrirplk.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtbauuezax.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtepfatcnm.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtlolinurf.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gtyxdhzzpx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtbckbsrtm.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtbqwmcebg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtfreprgec.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsuijltt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtxeywdhua.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtdtgpvrai.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtqajzvxzd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtpmgbsxka.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gthgpjhdxx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtqfhnscog.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtbzmhsoob.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtgvroogkl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtjfdjpnfy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtomaierir.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtvsosfhhl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtwokzaqlf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwgptmzh.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtqghzkwuf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtqsxwgvcc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvxzozhee.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gteuxsrqdz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtiemtbdns.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtxihsjnce.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtbolepedn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtnutyqlxw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcrozgbp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtipiakogc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtnsaefzrj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gttnfzttzi.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnvuxjjnp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtvqbzjrdw.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtampmrlui.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gtxtglaakl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtbrjhbptr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtkgrpbwxw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gthpkfkoha.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtldanqkzq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtdjxjraph.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtkucihlcm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtrnnmyaht.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtmmlmwaob.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtvrpuqrdz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtjwlwsuuc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtuxjvzfof.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gttcjntmyg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtrtbearzt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtjkwqtzoh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtgsmnzdjf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtyyxxmnmv.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtzworvyiu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtwvjjetgg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtmmqpletu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gttjnvblcg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtfzmasdpb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gtraiqibxs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtmyxxabyf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtfdrrlgrs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gthffpsupc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtndempeax.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtrkctetul.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gttacvgjhs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrasnaxia.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpzoantj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqhlfjqh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gttpfweceb.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvmzjnsbm.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthfeuvbhw.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfjzpqbqe.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpmguyaya.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtmdljwkos.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaqhnijdw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtzidzystp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtnurmppdp.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtylykmtgq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtaipgdscr.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtirkuflvd.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtndtcmmwi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtbzxmehhz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtlzlkhahb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtdnfrzomh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtbepkpkei.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtyypgaqgf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtadsckjum.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtevkofsvn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gtlrmixxqm.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtrfcnsfrl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtmjvxiszx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtyxjpccrw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gthekckcju.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteksljikg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdlhamap.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtnmaewcta.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gtljnawmir.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtftrwnkzj.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfqbflgl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtapyixpka.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtrxshqgfo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtjcfydrum.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtarqiuibm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtwecrnqgi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtipfbzzaa.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtybceqpgx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtqtjlqmxr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtuztqzpah.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtulaqjkuj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtlsecjzwd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmwvhnujc.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtczrwlmqr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtqkhwjoaq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtayohlrzk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsnzjithv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtaldackzx.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujbvskki.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtlshxsewe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtswwsluif.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtefpdzwbp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttfynchdh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtjmmtypam.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtdxupbtzr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyswegher.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtebncmhgr.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gttsyfepdd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gttnclzcil.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gtdcjoatvx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtrqaavlmm.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gthkgtrpjo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtszglbhau.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtyhxqiahn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaxxbotb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtxypusnfl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtferxxbxr.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtlhptufiu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuuxqmqtj.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtlxmxucsw.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtlbdwjbua.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtvbvfivtx.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gttetwunef.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gttltxcqyd.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsnqlcqor.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtjoiavork.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtswxogudz.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewkwoluc.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtgofykhbc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcziquqzp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gttyrgnekb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtwnhkwsmg.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtaslhdlld.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtgxxpcjfd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtztgdbsqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gtfgfaocvk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtqmyzacju.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtkagmawmu.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtrfprjped.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtfvbxxwyn.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtwitezpgr.html

TS:   name: string = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtheknpfyg.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtjqemcyzq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtleidpqcd.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtrzkfwetu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtlwadxbok.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtcczkvnyw.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtrmgbotok.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtxyefxvjh.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtwxpyoicv.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtqdrckdmm.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzwofmfa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtgjjizjnt.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtyqgcbzxb.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtuxshqvzz.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtfkddwrve.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtuybqgayd.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtigmdzrnv.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthosczicp.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtubozruyg.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtmnryatkc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtsilmvnkb.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqqnfvcv.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtyktiwnxl.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtedmcovjz.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gtwcivjqyg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gthdptbxdu.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzbsivxnj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtynfngwez.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtujibgypb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtngjizosj.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtiyfkyusx.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtccjeqdzg.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtyyqxvbqy.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtsgllrsgy.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtedrdqcrl.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gttebvusgk.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtyzbkfanh.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtopaqxmzo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gttfiphexe.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtukeocgxe.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtoyjpgbpb.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtsstzcvkr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gttsjksxsr.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtiasezdzx.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtfftqwgzq.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtgiftbdsb.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtxorrfyse.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtylztwrgn.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtwqcfjwhu.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtihqwafgy.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtclqjoabf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtremzbhgv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtiuuxqhgp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtlizvwfqt.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtummthgqj.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtpsmbawqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtggvymaut.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtkwucexuz.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtqniutcdc.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtgpufqhfa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtzygiuhlw.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtuhamxoec.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtlftaizgw.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtqfijanwt.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtdcfgrmot.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtrtaehiid.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtxmdrnevd.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtrxfiqjak.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtjjdxtywp.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtdmszxxhl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtofsuvrey.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtobggjabo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhrlpvgn.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtsoxcwcgy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtfenxeagu.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtuuguaopo.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtqjaawcde.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtrjhuboyh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtxgmqddlq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtptuhextu.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrqnueupt.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtmjflgxcm.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtrapsiwzq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtzhedcukx.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtgllmxdih.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtlcovzefk.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtgltebnts.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtqevaotad.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtmjcoznbd.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtftjzhvrm.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gthswtnyvg.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtymqkbxuq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtryvntaeh.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtjufkmxpj.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtmmrqpiui.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtatpslxnu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gteqvrawej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtnrowdsmc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtiytmfibn.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtiqylhpoj.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtzgavdeys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtfplcqmsa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtwgjsruiw.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtazjewtml.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gttmozjmvg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtjpjbgagb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtlsxuklsf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtgaessixr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtaidrcczg.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtpmbionwc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtdgnmykqv.html


<!-- 参考信息 -->