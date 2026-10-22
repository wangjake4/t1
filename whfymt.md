代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2ijsqxrzy.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gt2vptppbhj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gt2bfjfhvec.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2qfxqsujb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gt2jgzemckr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gt2yjgaeobt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gt2udkdncdc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gt2upxmsoao.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2nbejrndt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zzdwvxfv.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2ufmkmvtp.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gt2yjfljqkt.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2solvdkyv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2sjykpjnl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2fvzmfbry.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2judcyjmj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2xfhnzqjo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2ukmppanl.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gt2zgbwfaja.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gt2efjhzmmu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2bxluwdir.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2araozkex.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gt2kbfvgyrj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2yzljodlf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ezchezpf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2tebicfzl.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2huheqzem.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2eozrtmrk.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2cpstwpeo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gt2apvbqguu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gt2jhpuuagu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2stmheluh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2uecpvtyl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2hpbbdbgd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2pwtkmxul.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2kivxjezw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2rhiftltl.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gt2ckxemvbr.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gt2lfgzzpew.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2bsphnesr.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2nmgykiav.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2hssgdazn.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2hssogvmz.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gt2yfhgczwe.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2zqwhuaqn.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gt2lafhoviq.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gt2ajvpctcx.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gt2gzhbcipi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gt2zvokstcd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gt2jzsvuzvo.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gt2buwkddkl.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2tleeswtz.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gt2lnpwwhlt.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gt2gjwwfqpa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2fuhfyhoe.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gt2glqwjsfh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gt2oefcndwk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2gyozgpla.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2gycjkrnx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2raonefwr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2axquyjza.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2osdwcrsy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2csdyeiaa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2zvlcxdui.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqwlkrxa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2agczmphx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2tsmqyqfi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2ebidbcuq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdvqppxe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2uvctaoqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2bnzraxbp.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2sljkyxfs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gt2ojipkxuy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgmogfyp.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gt2bisdkilh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zbtrpusb.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gt2biedsrlm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gt2ubkayqdp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2kcxamsjl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gt2geltqplo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2qvxzqwqz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2vqdkctfr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gt2cqmhjakv.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efiuemef.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2rqdaxbdc.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gt2gdtvtdlm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqewdhwt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gt2iyxvarus.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kswbdhou.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xgmdbwjb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2xgdjoakb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2atusduzr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2jpfskiia.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gt2gmkofpuo.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2habudvqh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2bygsjmge.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2ylpmwnyx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2kdamlaox.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2swiyanve.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gt2brtyxxsi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2ozludxqe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2znnnexhp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgzkngmk.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gt2dbcaqusu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2mipycncp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gt2yrvhbrqv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2broeqxob.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2jqexdxgm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjipmajh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gt2rdvzqcem.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yezxsvtq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2mrfftzub.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gt2cckoazil.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2xalharyn.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2vlymtkdj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2zcilbsbx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2cpkvqlfr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2tcjcltbe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jowjfymu.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2fesntlgr.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2afypzvsz.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxzoqmfj.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2tniuhnlb.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2syqifvqw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2siedcrjd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2idyknffw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2bprfmnuw.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2wvkvotlq.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2lxyomako.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2fbvblehk.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2stgnghug.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdgkwbzm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2nuefvwnr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlrnumex.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trcifmwr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gt2smuwcnlm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gt2tntepdms.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2qdvgcygv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuknawvq.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljiyvtwa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gt2zfwjucev.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2qraglcnt.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2fyvkxtnf.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2hqsbmpcn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2dibhodpv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2yxlbswss.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gt2frowzhsm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gt2qstnqxlg.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gt2jfvwtsik.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gosoooky.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2atcvzuzt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2gjsxvgql.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2yaxscrrr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2iepvmjze.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gt2ejvlqrog.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2hqiosqbu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyneedgk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2ovdpnaga.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2bzjfwpuf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2pcamzeji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2cczizkiw.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqgrkfwi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gt2kjkscxqa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vpzxhrol.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zukbhlmd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubqlsprm.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2mnxmklbo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzecgvxf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gt2nzcqjfsb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2bajphbbz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2omtxgihk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gt2nlqndksz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gt2oaevzrum.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2tqymwbdb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gt2efjdxfuu.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gt2biucxpdn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gt2haiadlmz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzhvzugt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2jqmawqhv.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gt2vvxzrgsn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2konrrlqr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2jksbafxe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2ndfjaiqc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuxrssig.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rjwdqnug.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gt2wohodzrh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqlwzozi.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gt2aytpbomq.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gt2maxopajv.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2uquaazaa.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2ngvscnkk.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2pkdlloeb.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2ujymdabb.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gt2zstqkmtn.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2rombjzex.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2wrldsrgj.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2zjvvremz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gt2qotlltbn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2yyitprdg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2uswpleqv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyqiarih.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2ptpkbrdw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlhqdprw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gt2vjqoyjwl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mxxbrdaq.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2lzyptrwc.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2pukzbgzh.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abyjlazv.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpgiqfvz.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2lmyimseo.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2okrtufyy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2dxzjxdny.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2ukoljrtv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2vrskjfux.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gt2sxnhbjtv.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nafhyhwq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2cpydbswm.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2pssworvq.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2gmhadlxy.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2rnnidltx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2imgumygg.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2gluhwauv.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2rnerhsxk.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gt2zcjpontj.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gt2xddknevy.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2ezxyjxjm.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2bwbfkyaf.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2nyyzecuv.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2jxxirwip.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gt2fzaekqhj.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gt2wzcgrmlo.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gt2yjblsstt.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2igxenqbv.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2xyfzfwjl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2laijvfcc.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgeluxjx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2zxdfipgp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2pgvrlbkz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gt2smquhrvs.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pabgiclt.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gt2izzxxtov.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gt2qcacppvn.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2qbzfhbbm.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2cxmgslgz.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2exqnfkbz.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2avphkgon.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2xcmznuni.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gt2armtxsic.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gt2dpcyscmo.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gt2okwcstvc.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gt2rcxihsxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gt2jobkgdcb.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2yqczygzj.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gt2qflfrpsf.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2coegvhjr.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2qiohlgwe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwdjqvce.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gt2lclkatvl.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gt2pqumbsjv.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2rscdnqvd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2nicorgea.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzizcepc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gt2uwezkbfi.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gt2ncbacteq.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2whdvuvdm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2bcnwgvoe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gt2sygfacxc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2kajgmqyo.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2mbhcfdri.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gt2qdariwrg.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2xnvcrbaz.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyezykkn.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2mrozibum.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2emwigkxf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gt2sztoqrgi.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2kldievki.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2zvmhrloh.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gt2zelcqvcr.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gt2xwhxcrih.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2iimvmhqb.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2rhnvcxyu.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2cstoetmg.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2hfdpyfve.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2btippmct.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2elzycjcu.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gt2gpcjjbmz.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gt2tvndlxkg.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2orpwpyth.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2jxtbxheg.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2coimfsis.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2tgowvkcz.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gxtcaxuz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2rocmrtbd.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2zhkmodeb.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2qrkebetb.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2gboqikbs.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gt2vodwdnhc.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzonbtax.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2wdjystwi.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2pjzwglzl.html


<!-- 参考信息 -->