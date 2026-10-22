代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gt2irqpenji.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2qaewqqsi.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gt2awzamhck.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xayhazdy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2admpadip.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gt2ihxhiwso.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2drfmqkjf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2txzylbiu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gt2gpnrssmi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gt2ymatusum.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2vizjgxta.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gt2yxtukfdc.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gt2iefcibez.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gt2kyfskkfk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nstvlrke.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2sueysmup.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2azjpzucw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2itowhjur.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2oauwvike.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gt2smodcgsd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2maxdqkpg.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2vzhxhkxd.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gt2tbadsefe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2npopzchf.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2pqqjykpn.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2mwluogcm.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2zwjjjnth.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gt2jeazjohs.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2tpkvxktn.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gt2hkucnrau.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gt2gduocndc.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2avbnjehz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gt2ftbuxseo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ngogyyqr.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gt2rukacqqa.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gt2lyoigqwm.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gt2objdzctq.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gt2isvxovmt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2eriabysu.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gt2icrhmzge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gt2uckdbixg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2rqujbwic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2njqjagpk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2eqpfoycn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2jxfhofxy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gt2fenqzble.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2vkmzjbsw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2flgdtlpc.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2lpwwjlkr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsuyfxxe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2xcuqkooi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2zvpujojs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2rjbubkrg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2qgovqsjs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gt2xjpcfiac.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2paxguwrx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2evcknzup.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bbyxnbhq.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gohqxegw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqbmnaux.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vybhizdq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2qkbwrsux.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2tpnbhytk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gt2fwzafipk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2nfvdcevu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2qgdyanxx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gt2gqdkfmju.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2azaiztwq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2uzzalaqy.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2uklrtjup.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gt2nystuloq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gt2rniipvaw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2dbrqzftm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buougqfu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2gzourmtb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2eghdissv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gt2svjvcuyd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gt2cdabmbka.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2xtldjddz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2bwfxczpt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2owmpnocd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2upgkjqft.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2hmhlsone.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gt2nwhhhvgv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2lpktuvzi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2hkpjfekd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2mmjnwjgz.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gt2lxnpurud.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2cbtqvktm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gt2klshujtz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2wnlkuacf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtrrvxtc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gt2kjcjzxcr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2hlsctmln.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gt2ronengdx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gt2prffmolx.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2zhzaioqj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gt2rvdgkrhw.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2yxmpwfhj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwfcrwc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2cdmmfsxz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jaozxwue.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gt2fgxpneqf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2gkygsjrb.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmgwcbwh.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdswvldr.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ggrqbpka.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2wympfktl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qzsuabcj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2spyemtgk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2ollxnutp.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2gwshlopy.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ryiegbvl.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2kswsissa.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gt2gkgjupkq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2oyalplzx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2yqnpldne.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gt2ccuzfdhm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2hpvjlfze.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gt2lucolfyg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2efbpmbwv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gt2moierixf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gt2sycubnct.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gt2ylupnnnv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qoqarjsl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gt2hnmjsfpz.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2wwtapxdo.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2lntrwkpw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiaipcfs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2olkbdtxv.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gt2yecbkehv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gt2grdhqjcu.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gt2iqvnexsk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2xzohlcgg.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2rwuwrezj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkvhuoxj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqjkluzv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpbhvydo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gt2zqqmbwuo.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2wqiedqrs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2frnauocs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2pousefpx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2zyzlmhum.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2tunsjycq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2naltjzor.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tdnfqagx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2diefkytz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2yejvbsgt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmqtycky.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ozhzcklc.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gt2ssgoceyj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2urvnlqyj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gt2hlvstxvn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcskdcxf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ktodretg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2hcnsbfjs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gt2mrkphctj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2twieqtkf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2jeefwpqs.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2iroakqva.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gt2vmpbrbed.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2qdxyiagq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2jvzqgpwx.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2iaphrfgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gt2kgrpaviq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gt2rrjsxxag.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gt2dasgnlvm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2jituozca.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2cgxikhyo.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2jprynvfp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2neytyvxi.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gt2ktkeapgm.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2rthdabxx.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ejlpowuk.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2gpjpqdma.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2cipwpswk.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2iguzatvn.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gt2ceyvwplb.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2nluztlka.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2jeqdwfwq.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2xusxoycz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2fpuacwnd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gt2emirndpp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2lxjjtesl.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2htnbpjss.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcdpzujl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gt2nqiqnjkw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2rfxtbbhk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gt2uvxxdpzk.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gt2hnkqzltj.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2qzucoubl.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2lxgsyyza.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2uabemgim.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2olyovnac.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2koflyhkc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2keglrzkq.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2edngnfty.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2oacxtnja.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2xtkixulm.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swnuqxlv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwkdzvme.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2tgrqclaw.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2vmvubupa.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2medgtvcd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2zbqftkde.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynnbtnxn.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2emwobpkj.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gt2iwncpute.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gt2csodrugb.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ltlxtpet.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2nicdrdps.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2nlpoowyb.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2xkibodqg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gt2hwgszcpq.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gt2adyfgbpu.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2heifvwfd.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2cshtodeb.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gt2iacabwau.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2abowhbqc.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oukespce.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2xdwcjujc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2asoacgkp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2reydqnmx.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2taflueyl.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gt2bfacxzsa.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gt2jtytqmfr.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gt2zndrskjn.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2dyualwlu.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2fjahmvkd.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2nbdegwkl.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2lnfwwxdq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gt2ipbpogkx.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjpolxgd.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gt2czkhmtlq.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2bthkysls.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gt2buqmnvko.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2qusqmyux.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2wofqpzpm.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gt2nxzdjhnt.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2foyihbrz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2mxlnvlub.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2xxcuyexm.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gt2zmobeull.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gt2iqlvrcsc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gt2spgurilf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnprxefw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gt2rwbgouyx.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gt2gkvshkmj.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2oxuepjcd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gt2snubrpbu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gt2ivlxdngk.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2lpjblacw.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2beezslqe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gt2cdrlmijg.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2nhnvjdgc.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gt2vbdtercp.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2csciuuwx.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2biowpqvw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2tvkdrpwm.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2nubgdfuj.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gt2ietaefrl.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2mrfbsqcs.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2gcejztkk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2evoastjk.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pcbcnzro.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rkihcwvi.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ubmafqsr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2oidyelkg.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2bzznhkdg.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2anvfiftu.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2unizsvsa.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2ashqgcsx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2cqyytfse.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2bicbznik.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2xysiqoaj.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2phfqjmud.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2pnflbqst.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2uzupccvx.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gt2gutngfww.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gt2wfyroprt.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gt2cifgdegc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cokjsvys.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2gxgliszx.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2rtcihqtv.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2jdlwecgq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2bvznmboh.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gt2govqvpcs.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2jfqsiist.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2ozrxnues.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gt2igacqtig.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2olosrisd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gt2rbqytoep.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2yzffxlek.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2fcbxvemg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gt2aigkztwl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2hlsgssis.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gt2fmvmjzod.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2oyrepsax.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlmxfxwn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gt2lszclotj.html


<!-- 参考信息 -->