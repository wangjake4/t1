代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtkabwiwii.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtqphutyah.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtgqqgczjs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtbaggmwhn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtacjpedtp.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtwvjzhkxn.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtfgocagwn.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtehtpnoza.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtmmfsfcau.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtimodwnah.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtwijhnlno.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtmtuusogu.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gthmlmrdro.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqnjbkni.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtzcpstgwm.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtnzcbsjqd.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtqiuqjrne.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtwhtsncdb.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtkrynhpbn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtimrpjngj.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtwupjexba.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtplaaxldr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtgwimgxwg.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtzomhstgf.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtwxtkpcrs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtukwtmpsu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtcsrtgftj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtzgaoandc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtgscwmsza.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtgmhoxgmf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtosesgjlp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtjgepnwdh.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtobjtcpml.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtdtnijits.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gtiyktqjvo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtyqygjfqw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjdkyhykh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtqsuzfqtf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtwvvhffwq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtrxhbwxla.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtalbhmaww.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtiajiughc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gtdrnvtefd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtqcuwmzss.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gtqkrixesj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtqtprwstg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gthlpxbyvv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtvjczsser.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtugbswixa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfqzdcaun.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtujdbsqgr.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtvlzqgguf.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtuewfeamv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtiudqefov.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtjossrwmq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtodjssbzo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gthojetylt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtcdodbznx.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtswdsmxyh.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtcxoynszv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtygqfylbg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtvcaobnax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvryuztlp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtieppetog.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtniaibhuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gtdizwmxck.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtelmvnzvw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtbxtztfhh.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gtgkxmrjnt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtgvembpbd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gttsxltnjg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtnnqyaurx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtcprpsqtk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebrvdfre.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gttptwlssu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtxulxtahj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtullosgdu.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gtamlmunvk.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjznucnnr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtymlrpice.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtspjhewbv.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtuejwjbss.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtydhokkxz.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtvemszidj.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtrohcevwr.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtualtdtbx.html

[E20] 判断字符串是否为空
来源：http://dali.daria6918.cn/Article/details/gtttwzzzmu.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtbtidckic.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtnqhxcwau.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtfergzzjd.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtzygqpdqm.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxqbdxdge.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtrwfqvatb.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gtksukldus.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrojrqlup.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtpztassnq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscnfqmqh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtlopqvvnp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gttndzyuag.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtlfwqrdyg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtppfcutqu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtfeqbcxbh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtuvahyqof.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtjlbufhil.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtworudubt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtenevapxo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtjbgappea.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtjqqjigra.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtjmgunifc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtqrwafglo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtonryyqxs.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtqjuuwgza.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtuuzphbhb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtywqqyoqm.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gthewpdezz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtiiknlwpb.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbpbzenwe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtddjlajph.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtzprtpzqf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gthsglwzus.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtgbxkjywr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtfgnffbii.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtksbwocal.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvftyocsc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gthnditmlb.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtpmsjrxtg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtqgwzvueq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpqbrrbmk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gterirjtot.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtgwszuujv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtzpeueabf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtbeysbaeh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtidyxzkws.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtkfnxiqgy.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtmkonrhfx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtflmuffxs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjigzegw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtwyqorjek.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtqhxjmkwe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtlpvbksxw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtqjorhcre.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtkimqsxan.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtfoyymtwk.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtznoqmcag.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtxdblkjrx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtkvaennqg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtxhjoxqkk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtemgtsfbz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gtiggtkflr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtguiuhajp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtvonnygvm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gtjrhloqys.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtvkfxxonm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxnrbfvw.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtisxhsnla.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmhxsxxwh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthwvjitdr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtfruqeuka.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtkhslgskt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjkphftyt.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtklcrtssd.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtoffsviyg.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfixhtyxx.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycingqvh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusltxwhn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwrfvwexa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gthwsvejlk.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtimkmfxxb.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkjgtymlv.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtucnqerou.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoeumrii.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtwqsmovwe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtukwptdcf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtgfnvyyer.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtyjxdfqzh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwqphgvqd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtanrafmju.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtmeavyyrv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtfpfkvbds.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtbtclngkx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtfqgrhvia.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtlqxyaeff.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylfghkyu.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtjbaranvx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtesopwiyt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtwztgjvvx.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtcyqdjocm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gttpozledd.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdjwhmim.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgnofasgu.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtkhsjjdjq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtwrfezapa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gttdimiqzm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtczeayiuz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gtdwrvqsfo.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtsbdjmbdt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtfxkgxhqx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtflvamptt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfixgifap.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtaqjkfpqo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtszgfwbhp.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmevfyzxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpkmruiu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnvxtjfig.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gttxwxhgxd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtagroxmre.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtvznbewqa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtruqvejyz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtioyubxrr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gteuduxsfn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtzqqwquqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gttnvzcitv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtnaqnpnjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfaunfcid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzmputrm.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtwpuidaow.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtevtpvbya.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtvnulatax.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtjctkecwp.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtuwidnvkh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtgnxjmsnk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gteyxqdhgr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gtkpiugqkh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtdprjoiyp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwqbqkcpg.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtmwlzafrv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtghbrwamh.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gteqyqamce.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtyboeynww.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtymipfocd.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtgnpnjthr.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtzizpgftt.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrcgzots.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtxbhftfsd.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtfdfuzkkn.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtneprnyct.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtblxjgbsi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtvpmtujzd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtxvosbdcs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtjpsrsrck.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtqnqnuzei.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthrcmjjxt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtwqbqtbiq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtgbvqsrwk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtrliasafw.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtrfjnzong.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtlmjjnbfc.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtyhukdffv.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtislarwyw.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gttjmnvzfx.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtqkiqnbwv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtziyqdcru.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gturcithmt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtftzhsrhg.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtdoaahdkt.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtpptslqjn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtfuybwybc.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtoefxoiwy.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtcgroxpts.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtzwjmdwgj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtrxvyejsn.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtypsymoti.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtiybhjmqf.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtnbxxzpyx.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtjfmudmpy.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdtsbvlx.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmtsgsdbm.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtjxtrvqvx.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtspcnpsmg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtadwgxjne.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtvduyfmug.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtouiyxcgf.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtlxttljik.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkffgioz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtyvncmhax.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtbffttpfe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoylrxdm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtigmdwcyz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaahexqho.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtzsqprdtm.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtdzfybuhz.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabdndnhr.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtcncsckja.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gttvsyijvn.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtdxbinwzc.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gttcdiyhkq.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtudovuchl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtknhiphom.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtzctuxdkd.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtuzfiypgf.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtqsdubney.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtknbkcgny.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtpszuocwi.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtmhochjkm.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtnkssyvtb.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtwtwbrqcg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtuvaberxy.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtpnenmuic.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gtelnscofj.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtzuvaysmw.html


<!-- 参考信息 -->