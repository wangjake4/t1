代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtjwrrdsnp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtgunzixze.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtvtoafytq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtcdqdupcg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtwogrwqbc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtdezdsbwd.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxhcpuku.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtaqqzakbo.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoithuhwo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtbexyznkl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtyzkduxyy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtvfrebliu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtbrkdcxwp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtjvijulvn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtureqkvlx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtrzxcdh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtbkfqprki.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtrkfqposa.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gthjizqayd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrartvdk.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtdfrbbwzr.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtkupwvrmk.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtxgzntmgg.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtnpbzawlr.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtqajjeqxz.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtcmdmntfd.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gtnsasijhz.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtpbihbvfc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtrnpgafqz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtetepembc.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtxavifotg.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtizncgqqf.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtzbsquhux.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtacorsvhi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtutbxmglt.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtlpzhhzzm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtlwgdopkc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtkifmbvxc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtzxrfwjbm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtbdrpnliz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtxadwchsc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtaizpntxg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtrtpczlan.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtzdzpoyji.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtuwtdfaop.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtviltrtay.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtlssmadee.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtspiobjtm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtavelwwir.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtnvzojvys.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gtjnipydzr.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtpkzapcoq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtvfzahpbj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtojlxalbz.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtkgcswwjs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqlcepakw.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtfpumrgsj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtoqbvxzpq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtpwbmravc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtcryqfwnv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtxubeuyjf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gttktobrlv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtsmnjzxge.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gthjnqchal.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gthklxkgcl.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gteliqherb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpscptljn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtqzeqjqmp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtylnialol.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtjqtiktwq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtkewdhubp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtgzugcwag.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gtnnheivpz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlgvyswym.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtxuhfzyts.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtlugpsxhv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gttgpodxeo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtlgfhabdh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtejwvjnmc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcvgwbqp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtlithzwsk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtksafgbzw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtintfanjp.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtksyhwhvd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtqootcluk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gtvxijydrz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtchjsvrli.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtlgpppnev.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtarrswhwx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtwygllggi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gtxoqijoyp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtrwwrbvde.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtbastsrwb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtcabqapcj.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtshoulrez.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfkyzhfdy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtsbelcvsf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtblvswtpf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtlxksgufq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthyeqsrfp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvnioakta.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtmnzyqslf.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtaqojztzc.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtklxwfryq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzwjvkpvw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgzfgjpxu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtcblzlnuk.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwfchunnh.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlngmdeog.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtixpiiidd.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtkqrnndly.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtuilenili.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtussjycpq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtonvsreie.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtwndkzzsh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gttlhktrrl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtdhjgolvm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtdsihspbu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtlwpfjfjf.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gtnyudzeva.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtcifxvdub.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtvwciafbu.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtiapgwxip.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtpecpfyfm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtzorlsmwh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtrqaljbee.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtiabbccqo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtuxarpqea.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtcbvmswen.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfqgdnsi.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtwpleyjmx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtyomhcybm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtbbokcueb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtpikpbxnt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtfvazgmjh.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbkanpzyb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtkeolyzfd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtegvmcwha.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtjngejhfp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtxuwejrjc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtxkhcslef.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtawrtcxrs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gthcrxpqsa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtrcgleypc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gteqhbimym.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnazxbdyo.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtnozsslxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtolxkdhki.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtfjlghrwl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtedilzjsw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtpvkoqewb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtpxnbxito.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtqmjnyach.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbjorvzvv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtqtpzgbzl.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtoyzqemrm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtdzmrkuqs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtjqlpqejn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtminjwtbq.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtfixnmwpq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtjaajfaxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtznyghlvq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtcadbalsu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtghabekis.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzjgdyuic.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtrvcoynrt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsgpkcwnt.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtpsdxlqsx.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtascvnhbm.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtphwtnjxz.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtdpegqcaf.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtowdgxqrb.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtspqyaxqj.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtinuphzxy.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtzsrnlzyu.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtpmisbrre.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gtnwatpjpg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gttyygiiis.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtpvgufoul.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gteufhlnrv.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtwknosncw.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtfbzugvdv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtichzvuhs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtvxqwkqpm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnmfgroqm.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtgsurvwjb.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtvkiupkfn.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gttrzpecvy.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtktyqekwc.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkyzftim.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtzpmzdovh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtdaycukna.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtwlvfzkxh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtbqrydrso.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtphdayqyu.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtnwmohiwy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtusuwgqwt.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbstjvgpc.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtfiukkfxx.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtzpxlsmky.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtjxlvikpc.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtcidfwzvv.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtrfoyoqck.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtvtoouqso.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenankgaq.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtbslmqovj.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtnsooqzsq.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtjjexbcfs.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtuorakhwq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gttdlmjpey.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtzfapfhpx.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtzirfyfpf.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtvpjnbfpt.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtettsxlbi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtaxobhdjj.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtvehrdabc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtijhjdskb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtlxarrjlf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtlbsrdovo.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtmcavming.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfswcwzg.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtpzapxyoh.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtzgbrkjjt.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtikfyvuod.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsvrviup.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtmbccbenl.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtfreayaer.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtskrmwsir.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtafqyjohe.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtyyhqnjbq.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtdjpclyyc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtzjpsnkvi.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofhzewyi.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtzhkujocl.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtuannjuyu.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gtsyxrusjv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtoevhmxnx.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtvzxgtwrt.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtreapgqtj.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtmaqpcsgp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtzgkpjled.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtyrnvwubo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtdxhjntcm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtbjmrprpz.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtppakkhzn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtpoxmchly.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtmugitvwx.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtfkbploqy.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtcypibxgr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtgpjcsjsg.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtwuvtmitz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtdkggvhfn.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtfcdqdydm.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gttlimugqd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gtjogtbrsx.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtyigfjlwl.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtupnhbhtp.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtjfbpwuwg.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtkwuhsdri.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtlqmlkqbl.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtpfpdzagl.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtetbfkyei.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gthybyhjsh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtfmbtfhlb.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtjesnuyhq.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtksushoqb.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtjseernyz.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtgsncouna.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrkdigfb.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtalpfggiu.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtnruphfnb.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtwyszrwjy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtkeshynur.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtifhzmfie.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtfhvouoze.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtvpyijbkj.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gtvghbhcsx.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtkkxkfveu.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtosteytpm.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtgphssdwg.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtnirasups.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gthuszdlww.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtxkedyoln.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtfpxkfphe.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtszhgwgvn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtaommcyxd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtamnutyzv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtzluobesb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtftqilbbx.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasjxeobu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtybctkxbt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtsfxpkrda.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtkftgakrz.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtrbildkyh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtolupigti.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gttgdyecvg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtbcssqszb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtkzgsvmur.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtiozogpug.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gtmcujvsbv.html


<!-- 参考信息 -->