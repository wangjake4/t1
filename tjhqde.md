代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2xtwpzsex.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gt2puqcahyf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tnrbbcdc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gt2syrrddof.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gt2ryysdsce.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gt2azjzyysr.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gt2ayhnxkmo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gt2lcxbemrm.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gt2rcvswfgy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gt2sugwaxmo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gt2bfeqjvzd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2hlanqzeb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2vspbdpxt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2qcvesaxl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2iuozcvtx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2xnuhyyux.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2vgpleclj.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2jjojgxej.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gt2ttnvqugd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2isofwmsv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2jhvjfufg.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2pgxosfqd.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2tcpiqqjl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2oxnmylvj.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gt2clthjtqy.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gt2liglimqj.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gt2pwbokewd.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gt2ipjfkyhj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gt2ekmfxxer.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gt2wcbxxcqd.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gt2hfptyeyl.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gt2ztqpfgtc.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2mroidsue.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gt2kyytkext.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2gmqtgdew.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gt2fjyigmwf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gt2cvowvlvz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2sfkdbvef.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2urnzlkft.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2zigwdtqw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2cmpfargh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ympshjud.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzzopyjw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2soxaekaj.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gt2jbyiqtjn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gt2rthrzgnn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2hqynkmcl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2xsnemevd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2uszuqfyy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gt2kpqmuvyd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kijtmuna.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2cizcvbif.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mklaonxe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2qvrhlfzq.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2pxujvchy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zyvjdvrw.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gt2sgheqshz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbxuewfg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2opkarmxr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gt2grajgvhw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2ojxrcnke.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpxjttoj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gt2fqenxhug.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2kydlllhx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2tvcgctji.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gt2jmhsvpif.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2vlfrtiwi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2mexjnedh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2xlcdmcqm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2pujmukvg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2ubwhdhnx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2udsojjgg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gt2fltxttqt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2nqyjwzdg.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gt2czfrruwu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gt2guecbeud.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2accrhpws.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2qachdhkw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqhtxqon.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2qqlpijrv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2yycrfrbp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2fjhaxqdu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2gkaepbfe.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2vxkqwena.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2qrodsszc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2hvqbfspg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2ntluxhrj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2oofjexxu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gt2vscgzvkj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2dkixlral.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkjnihlu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gt2rltfcotm.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2mqcbzmgq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcgccgfo.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2gcsmudmv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2bmvotqiq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uwmaghsk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2pfqmjtes.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2zqimjpny.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2aigfvuhe.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2alxrslof.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2jsrssrxw.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnnjvwgj.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2nezjptbn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2tjizznye.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ojukcyea.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzobjblm.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2gyjjmehy.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2yntxdmxh.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyifpppq.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gt2dvuwzqxv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2lxzcxiji.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gt2eyimjdae.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbvauxyr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2wuabbtta.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2ajztspvo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gt2nwaxipsh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gt2jpihtyhn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gt2bfhuwwvx.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gt2dkejxgnb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2kenejcuy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gt2ejgxfyvj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hytgwkcv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2wlrpqgva.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2ilhgdmks.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctixqjnm.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2iojrkpjt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2invemckc.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gt2achtkdqi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2zmzlxyyb.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2aqhhsclq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2funsmbyd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2vldxdrwb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2dewxpsyb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fciaxgmq.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2hgvasour.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwlpxdwl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfczxruc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2skekctgq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ostlhdhc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2tkdtpxtj.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2xmuwwgnx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2brdermmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2bqpqnpxg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2xeygfzck.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2dqbnwoqh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyamqdx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2flvrynxx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ktkvwpef.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2xypauzba.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2sikqmwwd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2kscqqpuk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gt2locahssk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2eeqcvfbm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2hhzisoam.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gt2nyelaozr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxrchpwi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gt2zgukhphg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gt2fodrnpjt.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gt2tfxghhzw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gt2rvrdgmrg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2wxkqbovt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2pmursxph.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2nacgmppd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ffmxvldl.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gt2qrikxtvo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2yafvcdrk.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2zlaonauj.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gt2tewoyktp.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2txcvngsn.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2aayimljw.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2efdhrwhm.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ppovaqxi.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gt2kpeeejwm.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2pwpxtnrq.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2assuqyut.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzyuokda.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2ckzrepqr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vyewexjk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2pkhioyjc.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2yidksbqd.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2wjtpwvxj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gt2slxvbgyv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2egurlaqz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2fkbnafou.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gt2butdemdw.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2jalphygl.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2cmadlkew.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2yxedummo.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gt2uncyhcqm.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gt2kedrcteb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2dkgzytzm.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2mlnlioae.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2msgftskr.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2hfcgbecf.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2ylxtbknw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2teinlzkc.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lgdgmiua.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2xntwxami.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2jrizlhji.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2zgbpuuip.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drpfdzbt.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2hilndilg.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2njhewurd.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2bndbznoa.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2vpabxizd.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2rydswkba.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2iretckzy.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2kwmfilxk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2vsxjgudd.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2wybqwprr.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2jgqvmeoi.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gt2tfegbbhy.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2btfajzzi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2pactlpys.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2wcjfeqsj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2kkulmwtv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2ylnesjpc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2zgspyfhi.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2jscqxdag.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gt2dsixhhze.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2obdpwiyl.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgygsdas.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gt2fozpfzdb.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2tohtvtvl.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2qakvxpqr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjsvgtx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2pmixnlfc.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2koqzvjbx.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gt2szpnqkdc.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gt2diyvgoko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2zrkavjvx.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2onakpjgd.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgmgtlqr.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyclxfcc.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2hhwpzshr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gt2fetaospm.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gt2fvxfsrcm.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2rgawaboc.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gt2mriicvff.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gt2lzyuerca.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezhluvxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2yaejykcz.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2hztutbga.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2rcyxrlmm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmknciw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2zrfgjnzw.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2abnksato.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gt2qqwiwwlh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gt2immfecvw.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2nqiqydoz.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gt2wwuqcnmq.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2yktkzotl.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2kvcxdwpd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gt2fpunttms.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2ftuzkjxb.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2pefpbwkz.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2mbllqqgv.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2xnbkgdsp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2uankeene.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lhjxgbus.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmoxcdxg.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2notnnuee.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2ptllsnvx.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gt2cyirppoe.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gt2qqsbrybj.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2dofkwlkr.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2jxskidzc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2lemmuxwi.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2atzqqzkt.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2mrlmbrly.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ryufyrhk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2fiqvbfcd.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2prpjaaxy.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2udqzixek.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2zbeqtcmh.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymbvstsz.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2lzimuypr.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2avpvwxll.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2hwibpevp.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wevsqxtl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2fmpkifuz.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gt2zqbbztwm.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gt2wabfdqqc.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gt2qzxilhbu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2uuaqryhc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2tifkduww.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gt2rnblmpgb.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2tenetezi.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2xficlnly.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2yownzuyn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gt2vxqnmpjj.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2dxrjmblr.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gt2qzdaizby.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2wgrxbdkz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2fyoahndc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gt2tjftgaho.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cynyzqad.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gt2lltkqrcy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gt2apvufece.html


<!-- 参考信息 -->