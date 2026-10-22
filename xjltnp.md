代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2excjcjyb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gt2cduzplcm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2soddwpoq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sghzbogt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2azklhnyh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gt2nekbdtay.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gt2pdrkichx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2dkyxfiqu.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gt2yocmxwkp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2yklmbwba.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2grvacyvc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gt2yakrwhpp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gt2apxfmnil.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2ysmkhyas.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gt2owjrjhxa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2jzjjfyve.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2bmxjjabn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gt2jvlkzfxm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gt2mmwkuqzd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2vgahzadf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gt2mxlnmwup.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gt2klxrpaks.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gt2fljodxbg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqyzwceb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2fgepiqas.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2gelimhmm.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2wqcsufud.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gt2lymlavko.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gt2ufwpvvko.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2tflshmfe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2sgbgbcxy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2reuncpby.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gt2neepughw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2ilvwlrrf.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2goksqhqa.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gt2nuxocsvf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gt2gxzszhty.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gt2dkhsvvnn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2tyzjmjne.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ilycdbnw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gt2kilmbtdq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gt2mdpxcsai.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2bavghjvd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gt2ooebcsch.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2pzafvtgk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gt2mulkjlsb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gt2zyrsbglz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2myhzqyow.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2jjykogeh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2dydmfnbw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2fpcqlden.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gt2alykszvt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gt2ikzzqrif.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gt2explsxmq.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gt2xazpfwit.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2xlaszcvf.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2imgxvsky.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2vzjseqhz.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gt2tsqzawob.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gt2mmlsxgit.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gt2ekmczlmd.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gt2ujcuphpr.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gt2fdjsfmgr.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoizewp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2elieqkeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gt2lmufpqmf.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gt2milzkxya.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2kwmyqbrs.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gt2cqzequkw.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2jqthxcpl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2djrpucsv.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gt2brwkswla.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gt2bixhxrjx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2goavxdqi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2ujlrhqfx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2pljeoowc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2rkyytfgw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gt2ehqccphp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2iyhfrnhj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2qwkyrkaq.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2pzvwxoif.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gt2rmktoffp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2ykgtneug.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2qfhonxjm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2zgevqrfj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2szdnhhlp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gt2lmruwcvo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2ttmebqko.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2wiahynho.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2syyaezpn.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gt2idzgsihm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jgnmndnt.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2bstnthts.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgwxdgcn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2dmaifozl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gt2ajmdcace.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2eaykczoe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2cynilazi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gt2pmqbuurz.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbygawkj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnlzeifz.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2amuoqdso.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gt2uyetaqvg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gt2vhsbvssd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zytmlfiq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2sjllvlbd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2cqnyqdas.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gt2xweksfqd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gt2gzyqscet.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gt2pewpgssm.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gt2hiiwduva.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2nkejhcxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2lgeuhztn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2somejrib.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2swquczwy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2ciaoyfao.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gt2xmtyjvmo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnrtymrq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkxgdrjf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlfbakz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2kgsguetk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2hnkwonkp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2epewmgmj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2xgybgagq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gt2wuifhdbc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2nmoxdons.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gt2jiehrhbd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2xwbrgqoa.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2utvvzgfs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2qiyghyhn.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2fhhnhnqs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvirjgyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2srgycqbp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2qmiekhcu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gt2wvuaesfb.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2cewomegq.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2sqkixmvf.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2byiheoay.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2zsdqyggc.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2wzasstdp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2gckaewbk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itqlhtus.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2xtctrndf.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2qfogltad.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2mnfnsdma.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2adrwhoqe.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtlphtgb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2zykjkhqi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2cezjidyc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2eiclkznz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2ussrhpmu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2ttsnahcj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gt2qqicobho.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gt2zsnbnrxi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gt2xhkvmqwx.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gt2fvezodrq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2hzpspvck.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjyyuujp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2sswjojna.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2afvpngyb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2xgktenrn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2unffskyj.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsskjmab.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2oldmrukc.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtsbites.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2gcdbfefb.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2atxjoivo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2epusmnwt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2yvsonabn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2ekahmaxl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2ermklibd.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2gfcpxlzq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2ftmbnddk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gt2mjgjnbul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2zyjcezdj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2gmzwydcm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2xpihkcfi.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2kkyoeryp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gt2jestktlu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2pxobcqfl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2egyshqrj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2rfqdvejz.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2qftqoyio.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2zujxfbsl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2rykfaywf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2jvmitazl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2cbvnxxjx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2lcllqfmg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwjzbklz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2kvebpyqy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gt2kmersuoz.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gt2egvkjefc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2qljgtsjx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gt2phslaswj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gt2igcfckfd.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2papzedmo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2fzbixhma.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gt2pdkpdlen.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gt2eqzeqflu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2pcbozzxu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zqqupnhd.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2raobyxro.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ynoepdqc.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gt2ciirjpoe.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktgcrwdd.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gt2gklcqgrt.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2cchsiagm.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2dargetki.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtkekdeq.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gt2opcfsafn.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2sbvzgsjs.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gtrtgsgs.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2utreupei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gt2gnwzjvhn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbtryxyc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2vliqznxi.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gt2mskecnxn.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2fwexotqv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gt2kgrgivoi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gt2fhrgjfin.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2tmjeylvg.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssoiiwmt.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2prsnabzk.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gt2jnelhffz.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2drmxuega.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2kosrthxj.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxoxlspb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2gyukuuge.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gt2axmtkbpm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2eltgwypn.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gt2ejaggtac.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2jpzlybbh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2aiastunz.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2nnsypvui.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2qxmgjcgr.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2ptrqmiqk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2oiedfcuz.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2vkbtucmk.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cablzgjs.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gt2avibutls.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2knejsmwq.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2dcqiulye.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2pmeroqme.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2lnyzxeif.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pztrkber.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2fhrfmujr.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyaumuda.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwlbxdik.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2vpqhjzyn.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2iktnudoj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lfiszefz.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2vszzuxbr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2vlfkdaae.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2vggpmkhd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2gmuwykrt.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjakspty.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnsdwqjr.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gt2ervhrdxk.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfocoydv.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujjldlbd.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2igeowvge.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2hwjplzww.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2zyacnmgd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2ubivzprr.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gt2qayhpegd.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gt2kkjgtnxj.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2rmiqcyjv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gt2tcbhhwne.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2ywvyupco.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qejkxwpc.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ehlxsluu.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytibawne.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gt2evrupfim.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2ckygsjqk.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2xzmxcmwg.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gt2vjgqsqxw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfwinmfl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gt2boktncgd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxazsjiw.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gt2nqcczdjx.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gt2upyuxsfw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gt2dsqjglbs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2skhiekqv.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2keqbfnwc.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2xhzemahq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2ykazrvdu.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2hbvhmsvu.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2jdykqfca.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2xhwlcxwg.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gt2aphwiqal.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2rdzubecl.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2cbswpsyn.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2gzrdjthd.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gt2kmfmpgla.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2dyobelyo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ddeziiua.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2aurgtspa.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ararwxbg.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2mngumhit.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2mouxqkyo.html


<!-- 参考信息 -->