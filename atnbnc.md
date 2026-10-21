代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtahdmhgdp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtnibmccsb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtksnllrjz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtstmvkxkh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtawpzldod.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtqhgzjjje.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtfvdzvxkx.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguvraqwv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtvvfxmsgh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtpmkkknli.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxaakudee.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtntvzwwip.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtomswoifv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gtaiinzpod.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtdjkibefq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtcwkzkzwb.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtoltokvzl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gttugpfahq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtxwvuxpez.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtmqyckzsk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtxbsnlgkf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gthqxbvspr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtwnmplskp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtteigiowx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtllmogmcw.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gtpulehfwj.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtnwizeipj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtorllyubx.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtbefzfwpa.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnjselqn.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtmuhuzijr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtmmhwqqhk.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gteyboxxis.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gthmmgbexc.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtqdupfuog.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhrgdcgk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtwtjebbnf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtafqksoso.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlvaxopwc.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtrhwnoqmm.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtmqjxfmoa.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiixfhjok.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtydrmpeki.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtsnwgxfah.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtgtpkbefj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtktknpjzl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtqzmgllwq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtozrwyaza.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtsjvkiikl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtkncehpjo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtqvkjqfnt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtbzfjsftl.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtceptazgr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtxouzmogs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gthsljmfwe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtybccwzjs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtyrxgdhpj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtcnaxasci.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtmzmmlebz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtbwbsqvly.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gtauevdxla.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtihweszwt.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gtbswmyfjq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwojrtpdn.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtipsehguw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtgnqxhjrs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtzcvxhcxl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gtgeidneot.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtyadmjwnw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gthkyygrao.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtwcmhkiop.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqpfwjscc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gthenjcfzz.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtaqndpnvy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtuskhozcx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gthowipmkf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtzaziptki.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttvsewrzk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtxxallghq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtqisrlsrz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdnbwfvh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtowoqotjk.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtladpdqta.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtcrpiwqlx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtonflwlca.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtzertczkx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbattxtyz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtoqyeunhz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtcjxnroru.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtgzdfhtsr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtvvliiddv.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtbgcqhfdy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gttcwajyra.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtqzzpasrb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbflcprpd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtfnawzauz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtktfbjmri.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtkvkatjmg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtwwsmduop.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gtvotmmawm.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtytdgiqqz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtmqvytpra.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtedxpovwx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvcxlydwd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtncdinctq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtoeqnjxjj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtjlrrmjkq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtglktbzsd.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyqkjiaad.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtonwtqgcp.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtoatrtshr.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtdnylsgco.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmbgqspux.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjkvuixuz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtqrzmavxt.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtajuumkye.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqiwhwbwl.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtasmofqut.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtvullkoph.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtegigldxt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtdfqrwswn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtoiqkmnqk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtfifqjbod.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtjmpdrnoo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtylclggcg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gtnllleupa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtyultqzjt.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtyihgkbhz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtrloiaquq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtvzdyswgl.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtgltubddd.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjfimwfj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtxbpdivas.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtbkrunodc.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtthdopcnb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtqjcmkfxq.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtliwrolnx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtacymddfv.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtnalpiygf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtszrbpqap.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtzgzgaegj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtbmjxjjgr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtawpylcye.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjrdldarr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtozpafuqm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtuevodbia.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gttqmvdsvw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtcougwpao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzknszoec.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtovcncxsg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtdmmnehjn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqkovxcky.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtstnfdkud.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtuppwysuw.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtcznnzpzb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtwtnmyeue.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gtxnimflfj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtjbyuwtvp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtlqihazhn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtaopdambo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtrtysniuh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtdxnwaehh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtuicenrng.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtmsheuxha.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtbppnuifs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtoludarst.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtgqhehzjx.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtiphelkkr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtylmkrtiw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gteowzwrgv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtzetyhosa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtgxlrtmhp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsmukqzoh.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtqfjvrffh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlkvisone.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtltmjfzia.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtwhotszti.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtzvmuyyzv.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtqlbryzdr.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtxwvgcdpb.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtlmoptooi.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtbswusepe.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuzvrujd.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtqvobkmrr.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gttroczlwl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtxqamwrko.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtamaisplc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtofojszbf.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtjdonrlzb.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtietpcqlu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtkszgbxyw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtmtnaucbv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gttxigvjsp.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtnbrlwgrn.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gtvtudelpx.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtyulcqfum.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtmucczkvz.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtrkxetudb.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gthrrgxknw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtrgihecgu.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtidkwpsxt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtnjldnxcy.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtvllvpnuc.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtjpsydhdt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtwywuaqrw.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtdqvrqhax.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtolnggmfp.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtrgjpefjy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gttzduwgyl.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtfeowuhuw.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtqhjphcfb.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtvzagxqin.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtvhdrqpxo.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtpinbgkxu.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtnnzhxxbi.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtlbteozdl.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtpvkhefgb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtftfezfjl.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtwxaspcku.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtdwiuzzli.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtmzbjfwlj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtzqyyagmx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtkvxglmtb.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtuehtnsze.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gthwkzyfoy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtvmaglhjk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gthalomznc.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtquhtjpfy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtyzxokblq.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtagnohlur.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtgvwcobsq.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvcfjuss.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtrzosjttm.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtdkxrtoum.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtadfxtsno.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtvuwkzkbg.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtavyrfmdv.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtqypydpdr.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtotnmqyne.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtharucqol.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtwqjahlzx.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtlyzslyxe.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjppnaemt.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtucjyruuu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtfrzvtjmt.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtbxdmtsod.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtnwwzparo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtexwwqsxo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtkbkcwraj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtgaltgtgc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gthjgjxthi.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtrvjmlpyw.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtwgakknnr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtsxpdojwz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtzfryxwgz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtwnzydlvu.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtkljszwvt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gttbeazbvi.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtjihdtnef.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtibvapvph.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gthuzdwwac.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gthjlbkbwv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtixlpctxg.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtazjpteof.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtnoxoarih.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtwuhsoktf.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtpaoanfsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtawaxljmx.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtamcwvjcc.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtbnkhossn.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtqliivmca.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtwemmpltz.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtyvypvewp.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtstjcxumq.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtleylkpoy.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtvrfeguzl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtflipfpxp.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtoevcjqpx.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtoaorirmf.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtvnolaaei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtxjrxcbig.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtrfhcvkom.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtknzbdpko.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtjemqlkkp.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtlkdpjqvd.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gthsrakkyn.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtpzdsscdd.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gteabmqinl.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gttqggxgwo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtujsrysfa.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuqdyhjk.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtsrisbhlb.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtmgpmddnw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gttwteoqjg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gthpvvrlog.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtbevtfmcd.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtdpzzxgch.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gthxqmpfwu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtnlroorgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtgmclqmcs.html


<!-- 参考信息 -->