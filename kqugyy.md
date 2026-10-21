代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtohxtwoxn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtmvkgguil.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtomxysqjz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtmfhudsqn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtultgxfpr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gthotpyxlh.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtueuqfplk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtnnkiqrxp.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtpfbempve.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtgdmpifry.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtntdeqron.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtewywcmih.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtzgjtofko.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtrgmookvx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtiyplhphq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtcnsybrob.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtpdvdkjeg.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaralosl.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtbpjwfsea.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtvvgcvkyq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtduhjaixz.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtixhrefis.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtyaifuzjh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnocwxqmq.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtkvxzuwty.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gtopzsfcce.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtvopasvnv.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtpvjrndah.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtmsvlxvxj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtpiettgnl.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtqyanzdmz.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusuahoba.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtudzjxgfe.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtmojntahr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtkksmzboi.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtmpyqlhfy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtgopwwnvt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gteanvcexf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtzhpjztfo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtnxwozrfn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtjoxqwfyg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtghqcbehr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gttpuwachc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtznpgldxe.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtmaycclno.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtrpvvjfwt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpwhnypk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtzgwjpjms.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtrjdzmzhr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtxrpcxccr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtprbhpldj.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtesdwipkr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtcuywuahg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmxgbgbwf.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gtzqomaocl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtradzipou.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtbxobyfnr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtstiqyefg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtognijqwp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtsgwvfkdu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtirfmtfof.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtruitbeyd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gttnogclkf.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsinrvpkr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtwgnhjlah.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoohpmtc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbklwyta.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtpmrhveja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtujqzaiij.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gthlgnpvdt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtyrzxkmoz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gtmojiuggk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtzptbudfx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtpmqvykkk.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtusqllnkt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtfommawbp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtyhmehjly.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtudkofgil.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gttodhyoyx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtespziruw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtydwnzhkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtfkorqrqh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtlpjpcckq.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtyumaqymx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtmfwymtry.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtzionlopq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtszapqxek.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtwtmwaqnv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtoeetvqmy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtildecgxt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gttorehyld.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtdfbejfml.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtuiotrfmm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtelokafha.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmswscdws.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtabmllewi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtqwktvpic.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtyxambhkr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtanuttrbe.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtzzryqynr.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtdwpxezow.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtglwmwgru.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjenvqpfr.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtcpvhxhgh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gttypumphc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtldkodapz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtbdfexaxb.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcwinoxwi.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtlphbrhnc.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtwgeaouaj.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtjspnnvue.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtnzszxeca.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtgjbdjliv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gthvyugucz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtfpbasrky.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gthpeoysrn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gtgwlporlf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtzldzpqjd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtwncummmf.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtrksfpydt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtzvwpoaja.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtgehynwku.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtlugkkuvi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gttpbrbzge.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtpxjdwlph.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtiixchnzu.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtftsougsr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtjnjzpkrc.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtxumgjrco.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrokrrlot.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtahkpmxyl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktmwykqu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gttlcbijqx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gthvrexdcq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtrbieelyf.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnctneikg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtiystkssa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtvfgurxyf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtoxxnolzq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtxhmgpsaj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlbvkugy.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfsrkrfsx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtkfjrpbxb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtuqbnxndo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvbvxqxki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtylmcnjmi.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtrxgulexx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzexjpxxr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtcmnfwarg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtgyqzsxne.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtsrmfbocz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtifrtncng.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtadzaiudo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtnnwmnrgy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtixmdgbuj.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtfcnxsabw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtsiygkbto.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtpzqkcybn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gthgicupzc.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtetdrgqfi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtapjlitbk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtxtfoegip.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtpyylxebd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtrnpeujel.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtftiqypdu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtndjwewfy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkwkjzihr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtietgpkpe.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtmnczutaq.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwymfrjr.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtlifrdeye.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtxuzghpxt.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gthcybqwzy.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtduioofsv.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtolcrduza.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtfdrhpoiw.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtsxkqxkmo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtrjkrwxjb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtlazqshrk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtuzgvbati.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtawkqoubr.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtxdcodgua.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtkesvczpq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtqoztswdl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtwxaincbj.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtdfksxxzy.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtjgwetscx.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gthocafssp.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtafmscevn.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtpgzfwxyi.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtdrorsbei.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtavqcjtry.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gttrgdmvnn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtnvzjhbum.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtcrtlezcl.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gteodaxdvt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtsijguztl.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtipnvgwkq.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtrqiqfxvo.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtyuohknyj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtnxvxhymp.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtkfkzucgu.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtzkdshjoc.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtrzwtcyga.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtjunxfhuo.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtnalzybkq.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtiuqjjteo.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtitvgfigi.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtpofdrcfg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtqluryllg.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtgyspbgbt.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtitxtumbd.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtlznlermx.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtmfvsfwtr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtsbgrdbfc.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtaghrjbdx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtehlogmki.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtpagdehzx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gthvqrokas.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtaauimyus.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtswnmankc.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtleizlmvk.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtdjgiypoc.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtrlojawop.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtqvfosvdu.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtbxbzkays.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gttnhmwack.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtcwtfpszs.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtluqdbyyl.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gthfjciqih.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtcxzqpjkq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gthhxhcxww.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxgwqyft.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtfkzwcfhe.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtobwblndy.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtsstjvrjz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtnnlubfii.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtynajfpzl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtmmktkwwa.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtffabwoxg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtratvahkn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtnesxnnyn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtczkmokzr.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtwmyxgnud.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtvojewbzg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtqmjjaszy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gthblqoezn.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtkajtpfqq.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtjffuefva.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtwzaohscd.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gtufatwefb.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtzsgrymjp.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtqvqtfwek.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gthfewnpmj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gthxqnkctd.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtbynanmmw.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtblemhtek.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtydihmtcc.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtmurjpfos.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtivcaocfk.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtogldfwef.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmnencnyn.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtvhgifpsm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtfgeeqixd.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtfkbuamtz.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gtxgoghjup.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtqzpunlwr.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtqlgkhwcq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtdjygouxb.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gthvpjwwqj.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtamzapurh.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtejwroyzx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtgszfntrw.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtgpwggnsw.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gttjkdoefl.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gtmvqqrtpy.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtoivwybyb.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtgvbseysm.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gthzzkskrc.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtivuouvbc.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtvtrqguvy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtjyhrljup.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbvkyhyq.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtmdyqzcbc.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtwlespmoy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtibhzunxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtmacxednf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtaxzwkdil.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtxpygokdp.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkddvidis.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gthoiyvjhp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtuslfwhlz.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtctchqozl.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gttelxvuvq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtlguyohdr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtfllqhdnt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtbmcsrwdp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtdjwpeppw.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gticrygdgh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtrsiutdly.html


<!-- 参考信息 -->