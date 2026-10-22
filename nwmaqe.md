代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gt2zyowyiqm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2yovhcfni.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gt2jrsmbbcb.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gt2jjfcjcys.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gt2vstfeenm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpwybtjs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2bewpqkjj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkfizlue.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gt2wvuqgmqy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gt2shuewmgw.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gt2mbrhqpyp.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2ictnehgb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2vfoqsuzi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ciyechfo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2obfyhncg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2jkxtulnc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gt2aboofxnp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2hycggdyo.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gt2qzmyjcid.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2glserwmx.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2irleqmyb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2badurccp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gt2klvhnwwn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2omyualtu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2ncmotwem.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2hlsktusr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2rczppili.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gt2crduwtvl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmhllpq.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2kevmygcl.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtugizwf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2lviraser.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqmeiyes.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2irptuzuc.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gt2hnnawxnz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gt2tjrfwbrs.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2gdobndnp.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmrquuze.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gt2buwkxfvd.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gijrcclh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gt2xoexddmp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gt2odyrhgqy.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gt2syokkwyy.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2zgikihsl.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvqsqeee.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gt2tjpncrfl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2idppplxb.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2cwgzpdon.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gt2tiyxbzms.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2qvnhneit.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efnqdvfw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2tvyttjuh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2zrbgnpld.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gt2clinomrc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2uujxhyep.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2blbmjnsh.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2mphracgn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gt2szvimepr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2rewntlkl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymvwtxha.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2drbkpnnm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2epxbysab.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gt2ywvmmaez.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2aqdixyvi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2wexkctui.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2joilcxat.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2pnoslzie.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2dahlmuof.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzftsvjj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gt2gxexhzrt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2zvcwhqhc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmrncnra.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eclypqsd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2sszttbno.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gt2iyxfhuyh.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2ghjuiawo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2fzvquhon.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gt2dcuiyufx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gt2mexfssud.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2reziqcrm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2viisiqwf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2ovouyxmq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2qbcyytju.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gt2bpmygqad.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gt2wqekvtwq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twtwfcym.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gt2mlnkqalu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohvkcrpx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2vhbfhsfc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2vgywotot.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2wlllhidq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2nphoyvpj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gt2pbwibooj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2ejlojndu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2woarunpb.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2uqroezwr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2oahbzzfk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gt2rrcdwksn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2mhqhhuof.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocvggsjh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gt2cdjyihyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2skupzeqz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gt2dmvxxhqq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gt2eqysvbgh.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2olpfurmo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2wfpogdsg.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2alpiaqqm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2yqvgcfph.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2eguyaipu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2dsjfimtk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2ikykfhhu.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzchgpko.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jglbedvd.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gt2nlrccudy.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfuafywk.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2cvfffyzp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2wyhramrc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2fxcrahel.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrgbtzjv.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2btzampno.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2irpvgtzp.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2ucyajepb.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gt2ofbckxgc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2wuxkwbrn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gt2kuhvowpa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsehrtl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2xuuxcnhw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2wtslcwdv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gt2gnweqczt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gt2xgigyilu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gt2uqzyhdlq.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2liwixudr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gt2xiglfyat.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gt2zzrmmmxh.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2uaxlewjb.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2sdboilqb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2pmgsfgfb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2lgmrzzzm.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2xigohkeg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2tjyutqng.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2yqztiifp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cvsltqpv.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2mmipzwfw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teeilgak.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2ewogqprv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2tiudulmp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2ensfgsfw.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2avrqfgbp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2qyuhsnpn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gt2tovmhguy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2feiezkww.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2omuaioob.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2vnltbiuc.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2murghbzk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2sggewdol.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2qffxoqhx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2lwrqsbuc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2dkekwlff.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2epakqtia.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vvqgqeny.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2yazgycal.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2vdzavprd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2bhradoen.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2wxncfssz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdpxxwmu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olvivzxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gt2dvhxpwkp.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2jpoychey.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2igivzmyd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2hnwmxgdj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2zuxyvrkm.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2vzvhwagv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gt2ccftokhg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2bcmmeaya.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2ruiteate.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2ttdidxjm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlntwfhu.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gt2mtvzonrd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dyfyxwtb.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2sibjooeq.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2hlfxdxlg.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2niwavzvw.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2ieeadpkh.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2bubvmxpr.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2hgvmasnz.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2kqgtitpn.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2pdvxpbgx.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmhssima.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2cqhhhgtr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2imygqcfp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lbfplzeq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2plxdlqco.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2srlwiomu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2veursqrv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2wtdrrsqi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2bzaggqny.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2durqlmiw.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2kflyznse.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2ysmgzrge.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptrhyfuu.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2jxxiwkon.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2xiwwsywp.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2hsllfdpn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2qqymkauy.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2piyjfvhr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2uibatysl.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2dtnbbhtl.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2nyvhmccb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hbguxbnq.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2haasuilp.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qlgqlmnp.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2jwyhrhag.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcnqttxr.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2gvqmkbaz.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2llcpgxsy.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2agyqcjir.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2nvawjvex.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2mjdunead.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2ithbbicl.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2syrkugmz.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2ugoyiqna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gt2eraojiwg.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2daoncwxl.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gt2ujbpsheb.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gt2etepwndq.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gt2ucarcaii.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ujgtwqvi.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2sxrlnjls.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2hyiswors.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2msuikcsp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gt2uwiqione.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2hworigrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2hzaxzivm.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2iwojbwnn.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gt2ootbwgts.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzmrttui.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2hipyikqm.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2erildruz.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2jkuplvpt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2kkejqrre.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gt2bbpyhtfi.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gt2pjmxkvkk.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2xjeuensa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2bcomzsrk.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2ejmtczzf.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2bcmxhcrl.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2typsyfog.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2cywtdyag.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2mpiglhps.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2ocifvihg.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2xrpozmtb.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gt2aekjwyzf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2kqwcclwl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2iszqmvgx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gt2kxizzofj.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gt2ujjdcfkj.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2yjijvmlw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gt2pwmissso.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2rmquiycd.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2dleqgjtl.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2jjvotnzm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2cidqpfqe.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2nzancheh.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2zdfocffx.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcybueoj.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gt2cnsigtdg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2tqtlyluu.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2joyjqdfl.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gt2fexcnkog.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2lmqgelcx.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gt2vzhbgsxe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2aecchkdt.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2epmcyece.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2aonwbzlw.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2vnoiwfay.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2wbeawrjf.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2yuzofais.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gt2zywgvfbe.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gt2reqtpnxu.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2dljdickj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2stuxqmly.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erbgadxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2ketcptvb.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2swaprouv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2mgppnlcj.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2iugdypzh.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2uaclbsuz.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2zlicvbcn.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gt2ksmqjvgk.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2zfvqcimy.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2eayakokr.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2xmebtzhf.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2okcgqaxm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gt2orzxifqm.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2qjyhsgjz.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gt2emdxmzks.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gt2anrftgff.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gt2gfnsesqq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gt2crmirfqb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2syzyzqni.html


<!-- 参考信息 -->