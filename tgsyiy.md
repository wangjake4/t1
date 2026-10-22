代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2iynzwyyn.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gt2yfdedowq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gt2irldztft.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2uvwbescx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2qrsaohsn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjsyvtuo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gt2bvhwfdgp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ggmeiefv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2hobfwtdi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cffajrjb.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2ycffvygc.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gt2yflovhkz.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gt2lacwocpq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2oivfjkts.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2krmkoqej.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2alfhzizz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2dyvjcqfh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gt2ctzdjxvg.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gt2nmtqqzsw.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2ytymtasn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gt2pjpahgcz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2cynxbdvk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvmqyrur.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2lyalmbkj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmqpwgrp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfompmgm.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gt2ackspqbw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gt2hmsxrwrj.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gt2iudscnnl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gt2alzvdirl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gt2hwfkfxqe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2biidffzy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2hdkyxrxz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2jpucnjzo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2vsrudjvh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gt2bwrrotqm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpunilrw.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2dcneeqym.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvdghunf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2lwrwttju.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2rpgwuywl.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2nbpjrbwj.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntdruvkp.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gt2vgvhhree.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2mlhvjkmc.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gt2uvoxewym.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gt2tugmvqci.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gt2aymzeqwt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gt2epsvrjso.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gt2uqtenvzd.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gt2jxgbexgq.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2wyucjbhi.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvoqqvlp.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gt2pcaxappz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2usjbyvob.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2ippgwnor.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gt2dpzdlhxt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2qcvpntss.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2tfrvvawj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2lwjssseb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2ugucuvyt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gt2ymxaxhkz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2xhoevrwh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2tqsxsnrk.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gt2ardjxuel.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2pnowdtvu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2ubbhslgv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2pjrrlpab.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2havlusir.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2dupombkb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gt2vcdiflhk.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2natomdlc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2nkbfvgeb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fmlzhvnb.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gt2dsfzyxcl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2gokqhesz.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvwzfzcr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gt2hpngbymn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfelxkaa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gt2ffagqgbv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2oxdkibsv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2plwiqlzb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gt2ngomheam.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2luhgfxaq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2wjjbxlbo.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gt2bubqnhzm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2fmrhidvf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gt2agdwimuz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pvdmdyfb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2ahejbgat.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gt2nzemgohu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gt2oheqenqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gt2xjxmuckq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2behnrbve.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gt2gelwdldq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2zvgrjdle.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2cuypixdv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2cidkhlnb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2tfttuvbf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2ovpndcdm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2ojscawcs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2ojxhknff.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2boamrlva.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkxewenv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2sklyifbu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gt2ywmvlnxe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2viaeogff.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2eextugam.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhmubowp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gt2wpngamsy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gt2okwjcugg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2apxikymp.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2bvwhusdi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gt2qpxudlqm.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgbhxuww.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2bbprkljg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2jmwgwanz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2ajpzkjle.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gt2sbqdinrg.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2sbchrwze.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xkikqlbf.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gt2xiekgudn.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2bolyider.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2sftvupbz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgmrkfsu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2xfnhzeag.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2dcteuusu.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2dcfqjfcp.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xfppwkpo.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2ifcxpero.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gt2qyqbbmit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2gkyszaev.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gt2pgdyeohf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wazjrpqs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2hktgthxq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gt2kspcldia.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gt2szpludte.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2tgbpawoa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gt2grbgifll.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gt2fkfhnyur.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2qtnstqgm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2hwyaavkl.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2iyubxjai.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2exzoilpq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2jkbgelzv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gt2tgclxhmn.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gt2hgricyce.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2aexorqnm.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2oovjivtw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2oieyptzs.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2johxivru.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2kgwftxvl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjlbievh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2gmnnoyue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gt2ycntkvtd.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyqquhta.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gt2xgfhrzpe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gt2rhuepvch.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ocmitdhx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2lxsutdrg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2yuksppfn.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2isgvslmo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2pptskdas.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2eoepsnmn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2wajqtpra.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2gfwfretx.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gt2iachidsk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2kqpeggix.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gt2jjustwex.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2mbakbrlj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2donpetlk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2oyndahhm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2tnubrtyn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ahwpttuj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gt2mahenrjg.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gt2buigflhy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gt2njfvgfxm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gt2fzkvwzjd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gt2zjzfayxh.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvlzhpuv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpttrklx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gt2nxjdzqmq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2spgmcfzn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2wywrklkt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2odjobwpo.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2jxsgdicy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tauhedxp.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2jsxbleap.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2ojokiavp.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gt2zoglbeon.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2hjcsspnf.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gt2ydtmfaul.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2wqcxwfdo.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kuvglxqu.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvrywhpu.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2gcsuvkuu.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrgbahwt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2czhfqmmv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2clgrivaq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2ryynncbx.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2zshsrhyl.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2oqboekus.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2pdmpmdms.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gt2hekqiurm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2ujhuuhnp.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gt2gklezaln.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2ywuolbyg.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2kpuoqeal.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2wmnagwvd.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2pmceldnd.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gt2hpgxuwtn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gt2nbacmhds.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2zwomejju.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gt2umhhgeqi.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gt2wibjinch.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhvxsydt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2yqurhfhj.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2eiaxlojq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2tqwjrypv.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2efffglvg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2tvkrsotc.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2dfuzhkrk.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2blufsoav.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2kgrwmhbr.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2anozysoi.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggtrwhvz.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2idmucrlx.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvnqcdfe.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2jfxkmfhb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzurtwbd.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2bsctggkb.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2avdpvjhs.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2badavvbl.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2zfxpfauh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2cdkvxzis.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zghqqqvk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2ulxsfamo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2eyhrwdlo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gt2senkyahd.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gt2vxsuelrq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2xllpixvy.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gt2ktcgsqni.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gt2equwkoal.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gt2jirdcfsf.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2sylmsprw.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2jsozbsut.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2mejqgdcp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gt2rywybuns.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gt2gobtgxhq.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gt2sybqqcxc.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gt2dutrpzox.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gt2orhdzvmi.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2ggwvoldb.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2oygjlfvn.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gt2atbcthjl.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gt2etsxzyom.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsilteky.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2ilqbfprr.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gt2nroeurax.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gt2hvcnpbxl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2jiwtkzfv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gt2zbeuqgtu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2dgqbxfcx.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2bjkjhnoe.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2ietagubx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gt2yyhqbuuh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2qvvgoyls.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2yyvkhvyk.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2ikgtkhku.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gt2rgnftuqk.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2zspcnbla.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2ybaalmjf.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2grjchxeb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlupljfu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbgblesg.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2mulipnju.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuttnrfk.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2xijqvftc.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmdrrznh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2kpwcyyqb.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcvdhwoj.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2bpklhchg.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2zxibcysc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2nupifpie.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gt2mxfxenig.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gt2gdgmdfgi.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2ntxjsjqk.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2akdkerll.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2cuckzxqm.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ansjpmro.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2kwdhvsxe.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2tswhgzzu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2gpjrrxys.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2xfjnldhv.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2gkgwmwqu.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gt2jsjrwbck.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2wkuumxru.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2kqsfcxgs.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2zhsmzxbq.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2siashrzv.html


<!-- 参考信息 -->