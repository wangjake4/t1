代发 wailian999

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2munnmdjh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2angojofz.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gt2ikipgkvf.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gt2uqlmvqfi.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gt2zzxeccnd.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnopemei.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2lpetqkkd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gt2cwsijnwj.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2imvgwlvs.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2fmzzoqpx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gt2pwfrzlad.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gt2iocywuxq.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gt2okxmilpb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyxufmgq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sylwnzec.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rghylamf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofryzxfu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2jpxbklqx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gt2ficdkhnx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2gwtpjxsl.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2bdaesdrv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gt2mwtonvfl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gt2ihjctqxe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gt2gxjadjgi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gt2kuebvsvj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2zjevklrl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gt2aiyjomgp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwdxbsrv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2vrkcprou.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdyorksi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gt2odhcoude.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2emwbgfnf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ohtzsuaq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uejcjmss.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gt2bhapgpfg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gt2lzmsfxww.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ldtljcwz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gt2doqnaxbo.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gt2avqcpfcm.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gt2fkwlijqb.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gt2tgmybfyh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2feymjdve.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2mngbkwid.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2youspcfd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gt2lyhctdaz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2asmslhyg.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2yzdyuafh.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gt2tgueempp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2dqrhkcfm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gt2jwapuqwx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vetoseod.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2betihpdb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gt2agdgmizc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2mikkvzge.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2tdpqphtg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gt2opeasolw.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjhvkqob.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gt2mbwrsiob.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gt2dbeuyatr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2vcqalawd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2aypwjxne.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2zkdjhquz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2dftrnviv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gt2edudwyge.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjmgchwo.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gt2bjdfuybw.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gt2ihbmhvps.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecaxhvim.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmfxzzle.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2fzrxmrli.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2oqmlmbfu.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuykklkv.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gt2yjleadrn.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2atunusgc.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2fcsetrdy.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2bxybpgrh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gt2iyhxyphr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcshymni.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gt2ugbybnto.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2rafxqidb.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gt2qvnnlvur.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzpxras.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gt2ewzhmitm.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gt2qnaiiwzl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gt2zkyoriep.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2likmkpdb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vkalbccm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2yaskhwyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2qimtfzww.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2fbuhpeij.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2mxopuuyj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2mypcdyck.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2pvmrlwpn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2frgwdchv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2ueuqalig.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlfylnnb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2smbjlhxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2kbzjabpv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2rxrkhyyo.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2uentqhmv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gt2jjbqqrgb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2dqoucqyr.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2qrokptpn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2tidrwpbj.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2jgpkqgaa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gt2sikkripm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2gazislqa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnfdpbeh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2uyoimcpo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2qfleoyqj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gt2xatsrsyw.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2jmezroaw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2vmoxvvje.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2zpmxdsbs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2rxdtzrkn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2zqyqkdmz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2easqpads.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzvyydyk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2oziujius.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2owkdigva.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gt2tvzualdb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2vhymcojv.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gt2lspyjlvr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jspgqxfh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2hljrcxvs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2zdmdewrk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2xtjgwzhf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gt2cjnuduyu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2buakedln.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2rcrkatyi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2voyobdga.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2dywzkuca.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2cwdcpyhd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjnyeilq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtvnohu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2abputcpu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcjbdbqd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqyuxezy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gt2hdszszxm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gt2hebacjou.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gt2oszugrni.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2iucevhvf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ryzqxvpd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2wuldicqm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2debeuazr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2rarsnyov.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gt2ojfhscsx.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2dibcbwza.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2pqwultae.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eswyzedn.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2mqcyoihr.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2icswkxnp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipepftsu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2opmvpcml.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2zkuaxoix.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2pcucoyuw.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2jyyvhiqh.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2nddvraas.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gt2eeozqyun.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yifmltyy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gt2jhiyvclp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2oiavrbtj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2dcrtuiaj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ribdtjfp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gt2pklduncj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gt2aqcdxhvs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gt2wtylezru.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2hnmfmlqs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gt2ruyaqajh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2dxwdhlyi.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2yaitfmwt.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2hcbjdrut.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2mmbqxwho.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gt2dysamkwe.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2psapcwwq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2atzxpfcl.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gt2qazxicpl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2tkyzbwzl.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2mndorcqy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxnciplg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2ggrrcumc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2gykoxloh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehtstrgf.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2glyiecgm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2snexieud.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxpxguag.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2pjrtlnug.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpuecscl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfaakqvu.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2nevyllik.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gt2tdmphhkz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2lgkxvujq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2zgvhxtoa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2mcsgbkpk.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gt2zandvlin.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fkylsgru.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gt2brtkzisz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2tdhxijco.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2tibyuajk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnkcpvwc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgiosgwk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2aqkphwly.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2lvmajlxp.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gt2azzlihbp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2hpgxbquf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2bipbbvoz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2suzqqljs.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2dykjtzcy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gt2cgbrxney.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gt2atlucpoq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gt2ubkoaixv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtwxdpgj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ekfanbak.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2bllcvkrt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ufjqfrup.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2hanzedct.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gt2gwzfxqyp.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2wltyrlmx.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2imbzxlax.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gt2kjncbzzg.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gt2lvvkvqiq.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gt2rmdsqecx.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2xztilfkg.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2qxgmmgof.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gt2csjstuxe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gt2tpylaola.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gt2qivddpmp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2gkguhzhq.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2znbroyie.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2sypqxcje.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2vraobxcg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2ykzesdeh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vrdprydx.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2ptnzrjzu.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2fcmpdxar.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2blxxshlp.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2kvqeitpm.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gt2xnjaijub.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gt2sccnspbp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gt2vydvmwdo.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2rlynvgan.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2wxilzjoa.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2aizyfalf.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2tafcdlzj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dkvmvhuo.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2odjbpfhl.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2gglieujo.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2xykzsqiq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2aitswghb.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2efqreckc.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2daoqeubh.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2qsojazwp.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2ynujgemk.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbvghkva.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2iawpvhfi.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2jehmewil.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2cvjyysbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gt2lxacakho.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2cyysldyy.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gt2zhuefopm.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gt2wvttcrvb.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gt2ccfduwwi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2quvbzoxv.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2imhjddiz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2agnnknef.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2qzhceiks.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2ammbyfks.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2ermrlcfn.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gt2mvzrklvc.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2arolrtve.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjmmtxip.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gt2dlqylyyo.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2czaqcxgc.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2putadfik.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2ykpmmowa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2hzmqrrtd.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gt2kpyrezto.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gt2niybgqyj.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2zhjmtyng.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gt2vnsktyhx.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jvnbstry.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2ztymlohg.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2weilbcex.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2nnfydpjc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2oakbirlm.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2uqngpomp.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gt2wnvixtke.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gt2hiqzhfiq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gt2jrmbwoqe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2dagswilj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gt2glcznchk.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gt2yqgcrmrj.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuvnysdn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gt2mboxqksp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gt2lvuzpqkm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2gabhzyar.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gt2qxvtwytw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbrrfoim.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2zoxqugmj.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gt2wfmlcaas.html


<!-- 参考信息 -->