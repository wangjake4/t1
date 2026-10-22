代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gt2nsrgslol.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gt2lvlyfobd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2hfounzls.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2gsnunppg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ibiokacq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gusomyji.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2koubbjke.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsagvddk.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2egcqvsyt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2restkjam.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gt2kiqltlud.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2npnlaxek.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2jrweuyrc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubizzuim.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2yiwypkef.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gt2ltuemvay.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gt2vwqjsadi.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2fafwuvtt.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gt2gotyipjk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2rbjvfhud.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2vairmoqk.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2yjmjmuyc.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2roqjnnsv.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gt2iskvphvx.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gt2ifkvrvlu.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gt2rxgetuwj.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gt2qutveimv.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2qdxbmcfc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gt2dgiswjjp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dldryzhz.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gt2vdcbqpfo.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gt2svvonjxb.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hywsjobu.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2bzdapeqy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gt2cnabufvs.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxgtrbxy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gt2klculjnz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2hglaxzmj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2aulrpxas.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2oygwdywn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2trtldbbi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gt2qztwcvau.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2yheacqui.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2uofxznyp.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gt2tvlpvrmy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mpggiwty.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2sldovrjp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2pcgayvlh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2cmzfaier.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gt2admciwws.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuskvttj.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejnwaptb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2bijnnuam.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2uvitazxo.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2ctqdaqho.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hgzallir.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gt2xpglfoah.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gt2idckossf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2ciarljlv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gt2zyawnhhn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2qfxniock.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2aslncaqs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2frevnvgk.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xrulmamz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2orwxaskc.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gt2zoznhpuw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gt2ipnpgewk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odmnipqk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2vhszdpkz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2fevxmuld.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2tscakolb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gt2rmrtiaec.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gt2egjfpnjc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aagoibny.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gt2unwbsoco.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gt2hzhgweqt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2aojcgzpu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2pkndginy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgjwpnht.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2ozwxgjtx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edgaekyf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gt2snsxmcsz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2iszwgcjx.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbcasvmt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2tcmwathc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2wwfogokn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2wuogxhhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2yrfsnhmg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gt2vswhraay.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2njhragmb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gt2cunanopz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gt2kyaelkny.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2wvpqmsel.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gt2ulpmctoc.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2zazivlce.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2lsqknlcy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2fbhvixpe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2pnffmyti.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gt2fqowhqjk.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yrqgwehe.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2zjaobvcw.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gt2rvpuyowd.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2pcrmpkux.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2bbdidvvi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgwgflmn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2iekofytc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fycesktq.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2jrbzlgzd.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2quagfyni.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2lnvnxpfx.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gt2kkazdjaw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbiwhlmy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gt2xbqdrouk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmutrkce.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2cwepnvne.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtzpwqlj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gt2fauijhrw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gt2mpzqdfoi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlycmzur.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2hnwmkwpp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gt2qagjnauf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wqpjpyic.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2ocxzovdw.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2afnhjqdh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2rpnzlown.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2lfadhoix.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gt2pqcnoygb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2ympdffwr.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gt2gnkodzwr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2cevzsktn.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2puicswzk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2napuvuzi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2ojtsujxi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2jqoqqrdh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gt2yaenupwu.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2idzducap.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2ewprqzhz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gt2icktzslk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2axietdvv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocozkxhb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2gcfciuha.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qxwuyjig.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2cfczgvax.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2qcenfekr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2aygfojku.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2dzljcmgb.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2rrzflgjq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2wacorpyp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2eawgcgkp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2zetpyojq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2tussipal.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayqygnpc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2eryiipzv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2deqajold.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gt2frmmnrxl.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gt2qkioeobt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2mbhgavsp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2wvuxiahs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2lqcivuhi.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gt2pghvcffj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gt2uncxeuff.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2chhkusgs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddpjnfzs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gt2kghwjtjs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hejaicyo.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2aqrxwnqx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ffcwnvyq.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gt2wqotxurm.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2ewwshblk.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2vxhkirpm.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2pxtjzzgr.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gt2scncrftw.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2ytcuwvxy.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfeghvjc.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2hqquswjf.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2muwxgsau.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klgapgjg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gt2zwraiipt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gt2gidfpnnl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2lpsczdny.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2spixpsyx.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qpoatkui.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjyeqidr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gt2cotzoxmq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2xqtgbtjj.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gt2idxjmyag.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2fghpvxnu.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2scnnjiqa.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2gouorrbt.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2ajcublwh.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjrxecre.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2vqnggeeg.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2havdrmkj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2iidovkzn.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gt2cjypmuua.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2tagftghh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2gainhlcy.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2qtpnpysv.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qleardtn.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2pvpglewr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2isnunogl.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hokfmpbo.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2tpplatcn.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buoevbat.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gt2ysomlgrn.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2aklllpqa.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2fvhuzyyw.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2ffkgyrac.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ttqlriyf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2vbjmwjiv.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbgqjrby.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gt2upqdputq.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2dxlkyjua.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvpkoonl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2xbubjgfi.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2lxmnbdtm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2ihnzbhqi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uiagcfoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gt2xbmqkari.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gt2dtwjkhrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gt2jmjubtxa.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2rlocrvry.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gt2upfyxxvy.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gt2rqlfrjvx.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2nosnchhc.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2hjwkeclx.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2kkjilhka.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gt2zrpccamy.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkxjuopf.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2nkqajpxh.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gt2xnxoigdx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sutqdxuu.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlviifdm.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2ghphgznd.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2agkalqet.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2yknsvwze.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhpxwwov.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gt2mhsfkiou.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2wrafvdyy.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2ekgaspnp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gt2pypglyhr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gt2zmfxpqwq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utnoupdq.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2rkzwjeso.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2aikcedhm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2pdrogngx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2ugqfzxlf.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2yrlwjhrl.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2ulfhviab.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gt2gqxacymx.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2bywpycki.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gt2mephndpv.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2zohwqsht.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcfwfhvw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2ubmqbvod.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2qvkziqcz.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gt2qfidqtmc.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohjkdiem.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukbeakqo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2fianhimz.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdjbixpl.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jtaoovkm.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aethvtwl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2asgnkxoa.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gt2dnsipxkh.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gt2gsbqufxi.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gt2isfmdrrp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpxdcfim.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2bmzxvzmo.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2gyroczqh.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2edvousjy.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvluvgcv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2bniwbdwe.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2rfnoyreh.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2yepjuoqv.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2clwpnhnm.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2wdvdtzdm.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2hldunrdr.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2wtmlxwoa.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2bfqslrfe.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2ejkcihga.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2pjzxjgru.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2hubibuot.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gt2lxshojlh.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gt2ozsflkli.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmpisrju.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gt2pyzhcrtd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmpeuegw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2powsfzep.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gt2zimqagsg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gt2xwarwmkc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2phsohwcb.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2dqbogegv.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gt2cbsoexpa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2jzndthnk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gt2fahtabub.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gt2cumnldif.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2qjjwutiz.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gt2dxotkcbj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2hbbgzxuy.html


<!-- 参考信息 -->