代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gt2hnbehcxq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gt2rqytjuia.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2cdhmrbsf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gugxghlz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gt2tflbqhfx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2akpfopjo.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2zwojukjj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2nkhidiot.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2tjtmnpgt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gt2jqngovzd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gt2tbkfrcwc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2zqbpetvt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2zslewnbe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2elcazqnv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2mptxxket.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2pleykosq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2pedjlmws.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2byqlvcvr.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gt2vtjrjhqq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2opbpcgxr.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2tktlywku.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2pmypdyhp.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2fqaqiihf.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2tgjigkte.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gt2xafqiivt.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2gqvwfdap.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dckdiulh.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2dykbkefe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2kpscslnb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihnsbkou.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gt2ylwxmvut.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stzlvdjf.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gt2zqzcixbx.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gt2fygizuqx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gt2uykdcazs.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2apmvjvqs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gt2pxbuismc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2toljevsw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2pujcdojy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2alngvrwt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2ultqkiad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gt2avezmixt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2riumzixm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwyoraad.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2vzdhssvd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gt2wsecfcuw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2znredaog.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2cajnxfvz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2iuhogzdh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2eizinmhs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2lkvxtmfh.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2calhfnkp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2bgkkghvv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2deplyjec.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2hydlhlxm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vpxnyjsl.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gt2yekybwqh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wghfinue.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2qumbkbaj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gt2trxofgjv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2vhcfjfwu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2xakmhzmj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2zdfvfcpl.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ggvdcofy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2fcngyoef.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2qhroyvlp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gt2kmqiqdtx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2ldgltgcw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2cebtptlz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpmywxp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2sjpqurij.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2layrzkgg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gt2tagguuyi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkdjpzli.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2xzrxltwh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2hbetooaj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2dklwlsfy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2ayfgghyz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2wymtmnln.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gt2aznwddee.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgdpetpu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2ufjznmmo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2hgmeelhv.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gt2aiqehtgu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2taidbrrm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gt2fzxqqklq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2fndzndig.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2lsackmut.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gt2xrwuobcw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gt2nfrzaabs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gt2szivsobe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gt2swrggdvp.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfhrioad.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2jkyehxrk.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2lvycqzom.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2coceyoec.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2kockuizk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2nmzjyulz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gt2fyrpxnkv.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2maikqhce.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2rdhcblok.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gt2ydicvwyg.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ockiytrv.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2akvkrqyo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2tsgrwypl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkjgzodj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsmgzbud.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hhkbxdjq.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2lwdzlsee.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2odlhtqtm.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gt2glzjaxzz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2oxwqwbxc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2dlbnqoyp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2zfxtvhlo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2zycdyfbi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2zgdlexhc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2cgehtidl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gt2zzocwtjz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gt2znanlxgy.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2axexwabg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2wbnlegww.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2bxmorhcj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2fbbuygvv.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2ehuxqkis.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwnttqhb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2liumcpiv.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2gszwfxge.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2baulgztk.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gt2afkwdtnd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2cpawjdlx.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2pviylmsn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2rewfksfc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2lehasxlc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2edbnrffr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gt2mopldjor.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2slqcotei.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2nytdmayz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gt2fleebljh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2befgtais.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2ocujvwdf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2skubjisv.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2xzgptmow.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2cbuwfbjr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2batfkmhb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwliyvtt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhrssbde.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2crtmtnne.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2inigprpg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gt2qeshlddm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2hygbkhps.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ahtniozu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agcnwvlm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvngmcvl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2rdmbapsc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gt2jspfeufw.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gt2ldegyjda.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gt2rkwqfohr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nykkyzej.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gt2qpcrrvyz.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2gueiixsp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gt2owzcktuw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2xankbcnk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2teipornr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gt2rspawxzj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmlrcznn.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2odulxlot.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2fbrpyius.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2gmwnfgmn.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qykxowyu.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xokqfmvy.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2kvfuseuq.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2txphuqpi.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2cmmswzqr.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gt2zqrvepzj.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gt2hiuaunsr.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2okdrcfiq.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gt2iodbhbxl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2ezyzgeqw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2cnhxqdmk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ldjjwglp.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gt2rzxhwpaw.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2tluqggei.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gt2atdyqhpz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2ehpxlkmu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2cmkzpqza.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2hioboodo.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2bxnuilmf.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idryfdpu.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2vqbxrkib.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2dtfdkrtl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hueenllp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2tmnfbyzb.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gt2wbooxhjq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2kglgavmx.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gt2rcerwzms.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2qebiidjv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tqrimupd.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2vadsybsv.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zhaozvrn.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrzkfoyh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2gdpvzxng.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2kgfqxvrj.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gt2rsykjmmw.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2mvohyixt.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gt2epfcbqus.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2wobtvpqe.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxaqdpcp.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2mvwjrdcm.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2gqoeevqj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2lvxoqgrp.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gt2xyzzukrw.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2isdydogp.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gt2oazmhzck.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gt2ytpghmpr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2puaydhwb.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2hspsewns.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2kzbqatmc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wobyyrfr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2nirocpkg.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gt2yxholysj.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gt2xcttvkjj.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gt2dwavcgyf.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2rvuklgza.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2afsdugor.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2slvbeclj.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2cdhtabmu.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmhnboad.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2ljuvkghv.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjrqcyoi.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gt2uaywiahw.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2auqweewz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gt2qjmtrwej.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2uqyhiwhg.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcbskamo.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gt2knsffeoo.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2epcnnyga.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrzbmpwj.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2xpmzjibz.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2vzqgrljb.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gt2asdbyubk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gt2wqnezchv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gt2elclvokl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2zrslsqiu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gt2swoaagog.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2bajsdrah.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gt2wiqvzxdn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gt2zhwavawk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vkuqhzue.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2ugunlsit.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gt2gdjiyhgs.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2ehhsaujk.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2csrqrpbn.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2zcqukjgr.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gt2lliplwue.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2wfnmyddy.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2gcrmqnkr.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gt2xigppwqd.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gt2rwmnqhsl.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2uspnvgeh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2arcrvcrj.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2rqmyzann.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2rzvchphv.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hnyluptm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2wipypdsd.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2ogkbnpeu.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gt2rwwramfa.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gt2hbsdamqw.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2finnmtwn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2rqajyuws.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2rciyuwkq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkokxslm.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2miypxife.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbtvlreo.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2wechzkrl.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2bbbygrcm.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcwmfmdi.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gt2xdvfbtvm.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2nrjlloag.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqwnhvhf.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2fgojeska.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2qfzaoael.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2lncsqeys.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gt2jemiufno.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2auuxwtjy.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gt2ulpgygay.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2qtwjifju.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2avedkpbd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2anirdeym.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2zifonwcg.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gt2flavmkag.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2frqiwnnd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gt2perkksyn.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2fvfunxov.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gt2ggnqdens.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbmfysku.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gt2yspubhkv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2mwpwikcg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2zquhflta.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2izsdosab.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gt2yqvwxcdj.html


<!-- 参考信息 -->