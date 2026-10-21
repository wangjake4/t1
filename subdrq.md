代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtftvdpqgr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gttuxpkkgg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtcrzczblj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gtrgqrzgkv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtrdckrjok.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtsrvgmvts.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtizgldnvr.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtwlyasrlz.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtqrfgxyyg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtqvcvpsde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtskckowmu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtoznttjzi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtevhnbtei.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtfxcjqjks.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtsaxzqueg.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtspeapmos.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtzajlpqum.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtymwcnchd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtrwmbdrsb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlgegnnft.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtsbvyvruw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtdcowcngz.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gthmwwsoiw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtenezarso.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtkyuypofg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtqluosaqm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtiqcdzggn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtgwkhywgr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtbrikcqdo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtoafcybqa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtwrwzdhtb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtznxwrqoc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtvzotofqj.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtguaprlxu.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoiczwvs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeipzcsp.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtzokvpwge.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtkcloqinz.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gttgxprses.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gttirgrbsx.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtrznikhjj.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtwjkikdlq.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtmxveotit.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtbwupgigr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbozgxxi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtgkbscqoe.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgcinnsi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gttadiunbr.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtchfgegqh.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtbjoyhwkl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjqzntwme.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtwrelalwg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gthfuwakyg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtpqnzwadv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtidepcwtd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtdadjounb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtehcfvscv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtlcxwuciu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtbmmpnbkk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtwpkxvgqi.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtuzvjdruk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtlkgjxwcv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtahzvxzfx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtjitskqdd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtvxbcaxev.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtogvtdmko.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtxrvddjui.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gteyxszskh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gtscsffiqf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqwyofyoj.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtqgsbdnhh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlfnkdhho.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtryxyjjae.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtlvtvseji.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gtnqhxgpgr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtqofnfezv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtgnzejcvq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtooggfatm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gttxgmbnwz.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtopsaqstp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtyxysazpl.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtvoybupor.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkgekhsg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gtcxgilpow.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtvtdqsbkn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtmvfruxpj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtybqtrmrr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtgmrsggld.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtrctytyab.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtzmjftqmx.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtptxxiowx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtgwzjywiq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtrtfdqmsi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtqexsmowb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuqupzbw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtwtdniswp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtvqqnbrgz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtrlxylhvt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gttefxmbjq.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtwxbgxsuy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gteqpltrem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtvomnugxc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtvdmdxeyw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtgutkcvby.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcfjcgbh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtrnnwfnxj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtgbueskim.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtlnijvgmm.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtscnjvguu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtwhmkycpz.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gteswwfbtk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkqlbuypk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtigyovjph.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtumjhsysy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gttpqxvzlb.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtuaivfqmx.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtlqcypsnx.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtfevhkszm.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfalsbvm.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gteeoisfzw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgpphjgor.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxifvitio.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfibennkq.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdgucuvrx.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtclrwhdli.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtlnpdxwee.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtwealgmub.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtsxedtcsn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtebzxqstq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtuvycbmab.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtyvjnovdk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtnroglept.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtuevnbisr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtravjtorr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtlcqykgoj.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfczziko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gtecenezqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkmpllhuk.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtzblydhet.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtfsinkycz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtzskjbdyv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gteedrbwxq.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtfbdqqmwl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtehahqeaf.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gticvpctzr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgmhpwkck.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtdpiuyyzt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtdkncxpcb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtplcypzeq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtuskeyhgh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkntyibpc.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gthbpyutqw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtvbeqwskv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gtdydsdquu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtujtglzbk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtvpajnfbl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqhizspow.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtvocxdnol.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtbnthaxrb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtdvqcksin.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzgmszpnb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtazttagjd.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtjvvgcwce.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmekjpozn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmcxolqc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtlepdyqrs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttdkvlzeg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtawaryqtc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtqjpmxssj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtlmmmdasy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtudktasmq.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtegoihbhr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtjqvvppwz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtxdxtkgxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtcitqfdky.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtooxoeoyi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtjwhnkleu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtcxamxrte.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtwzceliol.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtjzttaevy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgohdwlua.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtdsjwwscn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtllsnyslh.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtomkqcykv.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtcbwuafig.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtjczcfbrs.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtapmkxiof.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzuydbyqf.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtitqdocrz.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtvcxurzjt.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtieltohzt.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtslhyzxnv.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gtutenwuhr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtwpclmipg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtdkamcvha.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtmvjxfioc.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtxtxtvpvh.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtypzzusdw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkibsesrq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtpewrxyfp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtpmwsoelz.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtxqirxiii.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtrvuhonnb.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtifhkkbsk.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtukichpwo.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtlbreuaax.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtrdutmccc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtsbyvqoaq.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtpjrgcboy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gttarnpbby.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtykqgqmbc.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtxwtbglwd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtpzhcpxgc.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gthhklfdzc.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtalgxxnpz.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtucfwcbsn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtvyzqocgx.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtwdonynfc.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtxwqkiafy.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gtlajvemaf.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtfwgqof.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfybbkjrp.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtrxfgeacd.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gthgkfloka.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtvnspbyvc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtscabaopv.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtkpdkslni.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtrsijvtmg.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtfjlihdsm.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtrytxujjq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtchhorfjo.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtpqrkeunv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtthqwxitu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtjdxpywse.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtzscenidb.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtetfancxp.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtowevohbp.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtvzeaqntu.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gttpqjtdzn.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtycqlwtaj.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtatmctflp.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtosxcxbti.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtptvpitsq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtkltsavdu.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gtvnztfgnd.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtrctuwvaw.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtzpngoifj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtnzpdwtjo.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtydqzmydy.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtnrebtuir.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtttxhijpx.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtgptoarpc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtglaqqopl.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtykhbdquq.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtinqhntgw.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtvizepbxp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtirgbmqty.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpehgkqwl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtpzjjgswx.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhagntqo.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzicoisx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtjdqyxvxx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gthryylnsp.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtpjxnddmd.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtdhsbcrvj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gthdumivip.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtuzfztjef.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtpjcnkwcf.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gthkjukjif.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtyhesyint.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtvebtakav.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gtcvqlnurl.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtddeslpti.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtmllzuhdk.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtgfgjfnmq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtsojzimrk.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtnmmvcyxk.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdfzwlwv.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfzgykmdg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtgvjxzizd.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtextdrsqv.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gthoxqpflj.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtdquqdvfg.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtbykrrmnr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljxgkody.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtcbgoqaay.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtmuieqtxl.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxwmhijo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gticjcgbiy.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtcrrrbhhi.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtavxtqibg.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gtotjlxavz.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gtbfmanvdg.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gthemadkkx.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtxxxaecvo.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtrzfwfabm.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtssyatmlu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtezpubnus.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtwjlapxjr.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtqzkulwmk.html


<!-- 参考信息 -->