代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtwabwdfqt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtzyxgtdtr.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gthfoznmbv.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtvswkodqw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtgccjpthl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtnplelpbl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtlggihjmk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtrcdlbstu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtzhjzbrdr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtmxbebcia.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtdxqlvrbo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtbiklhkju.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtzcdypmxn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtadfspgkr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtwogvsqgx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtbxobtrpk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtzdvxgnvw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtriuzjslo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtqkjqupxl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gtsvowitiq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gttbnlpepm.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtemsommzr.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtpjiuvhih.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gtaryodzqu.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthukvbmsc.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcmqvdfp.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtyvpybfne.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrwmwmrs.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtrrzxkori.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtzgmwrcjp.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gttzdldigd.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtlrpelybf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtkthowfqj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtmkfesuaz.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtsvveoetq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwbycpxja.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtkjghvxiy.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gterikugte.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gthzsilxbf.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtcdhvpguk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gtwmhsisls.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtzjpelmzr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtbfmmczlu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtcjacjqyc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtjcefowen.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtlgpldlvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyppenpa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtehjgrjfr.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtfrytejsc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtfsnfvijo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtazeiltzi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gthsppaanc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtckhyswdn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtneiwsvtx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtrghwigrs.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgstpzky.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtwrixouug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwctjrfkr.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gtiuaooojo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlhuvpzkv.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtiilylybq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufalydpv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gthhhisgcp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtlplfknlx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gttdghmnsv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gttobzpqeb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtwgrnolwg.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjnkpkehn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtirqknqcu.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtizaipqxc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtuqhtbxin.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtgksqomgw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gttninbyvd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtgcmmnzbv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtxeogmleq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtmacqvfef.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtindbzwka.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtvdtqxavr.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtniphhfoc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtohtasdya.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtwmdbefqd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtaluicwuh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkfdpzyl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtpegdkubc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtlievxcts.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gtvlwfdgpu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtmgzhskxf.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtzvjiwlhy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtdxpnpwch.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtlalbagjl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtalquedur.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtqaxtdpcb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtqfanwtto.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtdguqbtsj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtagwefzhg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtajlttvgg.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gthujxzxtu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtqwlwwheh.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gtoswmevgq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrpypyjeg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmugdlenh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtzxhshfew.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtuvjztwkx.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzdgptlrk.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuncowvnp.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtfjmbxjyc.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdtzforzt.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtijbpgycy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtlaioukdi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfekeyjza.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzlnnxtk.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtffauudxw.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgrswbajo.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtblsdgnvk.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtutrxzodr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gttrajyxnw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtkykmqxlk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtauwxgbuf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gthztontdh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtdzipgizp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtodcqhhzx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtmnbfxnji.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gthuodnqax.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtlotxkqry.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtskdvrmla.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtmwgvndwu.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtyzwotjlg.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtjqvbdsuf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtplujsnwb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtjsvsymee.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtpuwgkgyf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gttdcvhfbr.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtgaawsafc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gthynayumx.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjddfpkny.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtwxjwamsw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtxrghdtdf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtjtojjlqx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gtebbsgezy.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtfxvhaqwr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtioxmtuol.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtldgsdwra.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpfdhcfcr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtzidzfflm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtuqbknvoc.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbioqwmsu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtungiucoj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbpeoxgkf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgvaqozxf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtkqpzkgrn.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtjchcmbkr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhyaofib.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtjeqxcxce.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcpajxzmu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrhtjdpym.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtqttlbhya.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtuuvwkwhx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxktudxba.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtqpbtqdfk.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtsjshdiye.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtmcbyhaja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtcrunctwc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtfjagqpky.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtmoteonfk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtthcxsrdq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtlzthlsxt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtqkopcitp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtqxyhgwdn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqfpxjocv.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtctbwwpzc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtybomrevo.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtiluwpqmn.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gthpkqglup.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtgcectnew.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtgdqvvpby.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtxtuzuhqf.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtwzalrozo.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsxcnzbw.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtixcmjgom.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrnwsvvf.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtrhnutbvr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtwzhcvnqj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtjvatpydv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gthvrpdtdf.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvkjtdtb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtcsqjlyos.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtxvpjcedo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtgurbqavd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtszlcwabj.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtkbhkzxxm.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gteezfqzrg.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtblbgbcis.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtagmgjnzf.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtcwiuqzro.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtcxcbiqxo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtfvxxwsec.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtkfcgzevd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtlsjhraoi.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtsuzqegft.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gthspxwwac.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtjbozbrks.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtacnrqona.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtjstfupru.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtkqgsmeqi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtctcumwbn.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtmqyqlwfq.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtlnmuqjxr.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtdbvfsffr.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtgsckgahd.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtjebfqgjh.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtbdcoodwh.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtawtemunp.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gthqjzvbaa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtpflptjbb.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdrkwswg.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtmvyqxacj.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcptxwdp.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtmrlqvbxn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvaipxfh.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtokjgxegg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtydthrosu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtbyncvqij.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtlwibfumh.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtaoxnzhjh.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtpxjkdbyu.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtihnujblo.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtxsikhucf.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtuzkhrict.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtzzmiorfc.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtjsoncqje.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyadrptfg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtwxgytbhr.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gttzthtidk.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtqqdrmaug.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtlcokophy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtcsuyxtcs.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtzlxbadet.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtpdpgnsks.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtiwitavzu.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtjyxkgkwu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtuzbxfzzl.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtdrvjeius.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtdvyuhkmb.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtfbfnzvpk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtqabryacu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtivihytyj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtuhmiwuuy.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtuovuppkq.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtzlcnwffy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtuxbiczqn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtoirxijnc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtpogbswnh.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtiutgxzbs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtaseggazf.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtnlycklvr.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gtizhtzjvh.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtpujwabjh.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtbdtubcas.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtwokgfhwn.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtzlxxlpft.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtkozpdnth.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtwwfgafet.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtgfwmsqkz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtwrdycawl.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtjsuogveb.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsapbjxks.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtsvrxjxiz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtpjrkgdex.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtxmezhylo.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gttrivbotd.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtruzswnnb.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtdppgeqwg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtquwdhjwv.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtremajnjc.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gthwjmnmhm.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtlvtbpdfl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtqggcnwcy.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtkbqbqvty.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgttzuehh.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtaqhoefcn.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtjpjagkwz.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtukmztmal.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtuletmrzb.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtdsfrzegb.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtqvxzamfj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtpyltswtw.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtbzflmvyt.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtkxtoyzft.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtsonlkdwo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwnngamq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtvgwybzog.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtmnyeqsdw.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtxaxbjqbe.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdntiqijd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtkansrxwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtebrkawzh.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gtsdefomgu.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtafwhippk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtgqdtncjw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjqzexozo.html


<!-- 参考信息 -->