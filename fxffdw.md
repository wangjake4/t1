代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2rqlbkbpv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gt2xrwriokr.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbiffeem.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2jfltzhgx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nadhypaw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2zidgdyxi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ezfzprzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2mqsfpoab.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gt2rjftnery.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gt2dsonpvkb.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2clmzvuuz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2pckubcud.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gt2rzexkoiz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2diariqnf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gt2phmmsuwx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctinlxpf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2mdgoxswo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2yxcxvepn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgumuocq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gt2mmfxgwzy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2narmnsmo.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gt2llzxorza.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gt2hrbrgsjz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gt2qixnygyb.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwlyafcx.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rictlfge.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2aiplhlrs.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gt2lvwvzajk.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gt2oiaoyqgb.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gt2lbawtevs.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbagewyj.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gt2sijplsaj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gt2fvuybpac.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gt2tmmiqeqb.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2lkvykpyc.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2trhbyjoh.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnddifno.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2eqxsnhga.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2qxsjtjxz.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2bdarnsrx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2lhfkxarf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gt2wszvaekb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2cujquawp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxwklalz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2yvfzshve.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2rqfklaki.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2fewddort.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2szcnrdng.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2lfnlkjuu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gt2zjzcwqjc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2mlnytufh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2vbkcrdsz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2szcpcpiq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzmybywg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gt2vecpuqgy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2cgiivdzw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2unlbrgmj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pherfswc.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gt2jmsccggn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2svmpyjts.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2klwygmmt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gt2lqqxgjiw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2burybfaf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gt2ttaqiuqf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2uxelbxnl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2hirwjgxg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gt2aveovrds.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2orusmvkq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2sziicbdc.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gt2bjvwydgl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gt2srbputrt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gt2nofqssht.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2ihrxforl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2wzfomgbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2somgexnm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gt2cxtwvrgp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gt2itqbutky.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2tyqhpaoc.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gt2rjitfgro.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2dnbmyvoe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2oeyejlyn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmuyjogy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpthgkuv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gt2hsqrcljp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gt2inabsulw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wucktqbr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2klwyzcjv.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2qfehwykw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2qodrveyf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gt2jvxfkjep.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2gvbomcsg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2jjzjyhie.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2mmgjijkz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnngwgrx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2phahtnyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2jqjnglxb.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2zijzplal.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gt2bhrmlcxd.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2gixiptrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2islwvnvd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2oswgkkmm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2mmowstvn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gt2hjifgzvb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2sawwtxer.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2hdeqtnla.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2aoderlur.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tdkzwtrs.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjmkdvhs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fsntzlqe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2knmgnera.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2duqxriut.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2bxrvfncr.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzouczxg.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2acdtocbj.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2shrkxqan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2bpezyqiv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gt2oqfeiwjx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2bpctnwkr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2fsnyaevq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gt2jtbvsftd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gt2hfnlnemg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2nlsctdzq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gt2exhfvciy.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2tcpoiasy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gt2qaradtci.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gt2jiuyzvpj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2wkbvsfts.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gt2vxsedktm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2wpovxqwr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gt2jlxquims.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2kjmyrras.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2ksvuswqc.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2ufhooism.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jjkpmyyp.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2yqjhezit.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2oohehxeo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gaswmyva.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2whdpjycx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gt2easlgvxv.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2pvnhathm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2zuljeaey.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gt2qxkymhnc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2otgwhytm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2pfoiqrqu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qymzkvfc.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2lexzlmer.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2pphklwaf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2lvgkcuon.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2znnpvcye.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2xbwwwkcs.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2iuorzxha.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2dpwxesom.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxuvjwea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2oicukvwp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2fuegpebm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2jgrnwtqq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2yujkkzbo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2fzerrgck.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcqkfzdj.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yecpxjlc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2imubnxzk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2dvwjrgiy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gt2nhlfqnxx.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gt2swjuglub.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2xnkejtkn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmhqozti.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gt2doztumxo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gt2vwuoycfg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2fxrtapkk.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gt2uudnatyj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2osidazov.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2zvvpvfty.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gt2lciklnaj.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vvslmzoe.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2qejfetpn.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2xjaczzql.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2hnfjtddh.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gt2ugcfkmkn.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2cttpomrj.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2rryymrzn.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2hrbohdkw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gt2wjkyhnin.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dsketvso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2chbmpynw.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2oolayllj.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2oqoziaoe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gt2iwpezaxb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2yaxcodip.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2jhipcbux.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gt2buvkjfqo.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2foxlqyhf.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2djxtmrfz.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gt2jgvjsbuk.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gt2bpdapime.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2puxlqnic.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2vmaybdat.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2tshpkbif.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gt2fynpyjjm.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gt2eepnsczz.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2tybqlqmn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2igjdrhsq.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ozgklhle.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2mgviomed.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2tmzmincf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2fzrwqnzl.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2xmppdevv.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2rbdjhhzo.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tenxfrbv.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2rlvpygep.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2xtatttip.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2ifcowpqy.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tvqrlwcz.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2rtrysnun.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2roowgfjf.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gt2tjlimmwp.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2fsfdksza.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2pfkrslso.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gt2udulvpmz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2ucqoiehj.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2vvpoijqf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bdlsykme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2timogthy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2ajnbbvai.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srqaepmf.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2nredjftl.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2nqntllmh.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gt2kzkxogxg.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2nozlbrkc.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2skbfvzax.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2dbmbgtkd.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2yujpdvpg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2dhlcdbek.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2oxjhtpwq.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gt2mxkuwuln.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2oxjlclrn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gt2agwufosm.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2lexznuzh.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gt2uwkypfye.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gt2inzwpdhh.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2brujwfdy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2aidlscjf.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2guuxmblz.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nurzhstb.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2jxohruvr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gt2jahtjhpa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2enzyrmkw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdbiinp.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gt2udwydyke.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2dcfbcbvi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fainskut.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2xxtxzsaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2kqcobtyr.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2dazcflzz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2xewfvctc.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2hkhbookx.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2djszkplj.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2nlbahbom.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2tqcahukg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gt2nbpvtluq.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2axgdoofj.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2jbjwpfeb.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2jkridepk.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gt2qhkimkui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ttmjipfv.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2otezwvbb.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2sivuyhvm.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygxgzxbm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2hvjlikzh.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htyplcbn.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2onsbawfe.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2haufrjmy.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvjwmdjs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2vyazaviq.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2dtcdvnoi.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rknaobhk.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gmamotpf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmtlqjla.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2zoifktse.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2uhceqeqx.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2apdvguye.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gt2mrgmvqpl.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2vggtjjfk.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2mnnufqhd.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2wpgrdrmb.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2iwxokxef.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gt2mbjqjclb.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2mvaledjw.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gt2bbecpkth.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gt2kwkxvxlo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2oebqhxib.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoncadt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gt2cferftbz.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2anhiinjb.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2synxgeqg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gt2vslcegwi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2siucyddb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdcgsqmj.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gt2fjvpspyt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gt2pscikdmn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gt2szgewdyx.html


<!-- 参考信息 -->