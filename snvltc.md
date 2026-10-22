代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtsqbocwiu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtoxwdjvct.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtcyxrvrbe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gthefscxuu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtuvmmuehe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtkjqtttke.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtxdejbmug.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtykniuher.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtgwppgsin.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtgcpqaina.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtxziburjv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdmhzpzke.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtpfkgejde.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtjbpvqbfn.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtjqycdyzf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtbrpuhvbi.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtwnnnyguj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gtoklkkyaj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhrgayan.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhrdfkkv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtbsktbokw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtdgnsurxa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizyjkvmz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gthljpmzwp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxbxxque.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gtfzkpjgqu.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtsnncnlue.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtrrgkkbgd.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtfhzvhewo.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtjrpfnhxk.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtooxgsdwf.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtljxojzue.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtjxejwrqj.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtkeurezlj.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtnccxaknp.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtruvcikxe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gttebzsqjo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gthasubkiy.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtbqfhtwsj.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtnvbkixoa.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcorndtxv.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtqwwdntjw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtzmwjajdg.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtwedqwpqn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtgkkdxjjq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtlvpofjlp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtbarnrbbp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtnmrftdeg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtnqewkhvj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtqmfaxivs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtduvtyktb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtwcnwglxk.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtbmhhyrmq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtofffanrd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtvpdhzosd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgyscfem.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtaonaxaqp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gttiobmnqp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtosaaaccn.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtxrexsatr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtbsuospci.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnwsbzzwh.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtsqwlskvl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthinessic.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtlhuftryb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsqknxsy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtftsliuar.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gttqxsegod.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtqawxbvhq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtpvbegsfv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtgyoenopj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtczbevody.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtfxfwfvyl.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gtbagmtrcy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtxlgfcovi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtccsogavr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlfbtsxdu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtkmehomwy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtrtkruwgx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtuwtxawmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtasoogygv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtoecpssbi.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtgzcfeoth.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtoyziuiik.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtkzzdzvjv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtjcqiwyvh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtmdtidzkb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gteufrygnp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gttcxoxpmr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtxueqncss.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gttdhgtinr.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtdwlrfabm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacqpgmez.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtyxvqndmv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtezizcelz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtqkowwrup.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gtqdxzralk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtcqgolldf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtuczmypsr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtvhbiifng.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtawbnrklg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gteduvsray.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtuzommgbb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbdgskxrf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcrkyrjev.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtnrqhzowo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbbyqeps.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdgcltbtd.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtulewqlus.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtwdozqzxs.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoganfaw.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtxhrdkfwh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtiikrihqv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttvyzmqos.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtbphjgcki.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtphtbwmix.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmrkfgypy.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtqlwvepct.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtnbqowluk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtsyiejdeh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gtlieuvmya.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtsltztkyg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtjtsglfgg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtzwpjbeih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtykjveuld.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtcsycgvju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtfgrdsjsx.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtebzzpfuu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtywlgfqva.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtxpjgdpnp.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtxquydpap.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtunybtiok.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtlavhtclm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtldmkdzgc.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhtgugge.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtfggpyfkf.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtrhxvbvwq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtnvjlpdnf.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtoikzhsqb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gthstoqisw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtactumpvr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gttxajevpb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtndhmyrbw.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwwyqmahf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtcvaolyuo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtzeounleo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtdpsqjsgi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtrianeznc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtatszeyjn.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqatoobcc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtdndaxovj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gteemzcrbj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwittlhlf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxeliyviy.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtctlspjuz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlbrsapik.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtggtjrfso.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtswonymvf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgwxwnacv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtztvcnmsq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtcaujgnfi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvssxpxgi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtkklfklwb.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxqtwebn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtqjcrqtzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtzpxgmlaw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtwebfapkj.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtatiwsaut.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtzvdahaqj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtdtmzbmeh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtgsclunnd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtpllbaxgc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyieroqzi.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gttjhulqxc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgoeoqiqe.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtxobxscyk.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtmnunpdsv.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gthbxecamn.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtghbxvrqh.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtimikyymg.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtvukaclwy.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gthqqzkewe.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtctyfkazx.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtxfltizxf.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtepjdzyqd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtjczfradc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtfopipqby.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyootdrmn.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gtignruuel.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmlnrzeu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtfcdyyklf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtpogwdyjf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtuvinykir.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtlumaylwg.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtsnljvtsf.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtnelcmcty.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtcordgide.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtjfbdfmbu.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtqyedhstd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtfkzhhpky.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gttlchoaaf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtgopiriwm.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtwbkatoue.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gthsfhcdku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtuwpybiqe.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtaveifsue.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtodytupgk.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtuzzwkymh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtvhfeqrtf.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtiotgrfjl.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvpjyadx.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtxcgddzqd.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtjwpgqszq.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtjpsthekj.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtnxardhkj.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtlswwnxhd.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheyicqvu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtcpiwnlbw.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtzupkqfiz.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtbillzhgw.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtotiojjeo.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtbiffvrkb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtygieavak.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtpckkwnmn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtioiyhvif.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtpuzodtkc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtjspbqifc.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtsqdhbvvd.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gththklruw.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtwckutnvr.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtimpjnbpn.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtdhkhiqzs.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtvnoimbsj.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gttauvkutc.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtdkqjtgdp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtppgewpsq.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtznyneswa.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtqoeyeqse.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtgofkruhg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtmpbzctzs.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtijmdlula.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwynmwuss.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gthpylyzlm.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtsahusoqg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtyxhcwzls.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gtyikwzaxm.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvcltlii.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gthfhwyask.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtcikhtjcc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtxcgzwcul.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtlavrloyp.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtxfdeevtn.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuvbpmih.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtfmcegoyh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtcbuctwxo.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtugsbcnka.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtdbfnkyvh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtnjonedqx.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtqjetlzcv.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtbksarjjm.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtexskuywu.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtmddwfgkz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtupzdbngo.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtpzmfgzhl.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtsykozexd.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnlhpmih.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gttioljsye.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjarxmfh.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtodtudmiw.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtkqzwxmur.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtclmdelfj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtjzejqttd.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtujtyuhkw.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtyqjzsouf.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtancmfqjs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtkgkqzsht.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtoonrwhkx.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtqwplulxd.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttzzghxyn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkqyxpiqo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtajtihtor.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtubwbgbsy.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtoixrmgev.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtbkrlpaby.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaievwvy.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtnrliyvrf.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpdaskzj.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtqpnhvias.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtbdstlyqw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyhwvcvr.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtaozgrzpj.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtvzjqguvi.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gtwohudbfj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtclnmghbh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtbpttshog.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtplwilhcj.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtytaludck.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtmwyvxkff.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtosmwxyda.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuimygyd.html


<!-- 参考信息 -->