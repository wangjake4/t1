代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2ynwmtgeu.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gt2natirfli.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2ntefpolh.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2wjtzvslz.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2cfeurevc.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2fjasfnrb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2aaxhjclx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gt2hkeljayi.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2mflsvfsb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2zmghhbwb.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2tzazwduz.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2xwnxhcpv.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2btfhpqob.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2vjtuijtd.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2jnmcumbv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2svktdagv.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gt2zjczoqvd.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2qkttdphh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gt2luoljvfk.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gt2ehthjryb.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gt2poonqxzp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ozjkzqrm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2wectttvr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rgedyduo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hspwlmon.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gt2ygngllig.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gt2eplofhhb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjcmmdgq.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gt2pgzvoelv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adqbqdwy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2jbmejkvk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2lnnbjnth.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2mpfeifyk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2ttmebagr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2dokcxydq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gt2dgizlbgc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2qhyzgxfk.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2jgppinwb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2daolxpdw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gt2ugghrbsh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2hxfkaiar.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gt2rowqdyre.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gt2psmxqgfp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2xwiioeoz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gt2gjsuhcwn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2emyfmzvp.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2meelmtqy.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqdaetrr.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gt2nxoiizhb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2qpeppqyo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2yginovcm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imgjohna.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogafjelg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2unsnpbbp.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gt2vnhmunmq.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2dtdbptrt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2hqtseyrf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gt2eakhmkmg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2trkevbrq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2qtnusloy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxldgnsu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gt2jshapgaa.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gt2aatxujxf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gt2ugwnsmzu.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2lqxjwkja.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gt2xpfagerr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gt2qxhfxfjv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2rbkgflaq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2imwzetnt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2bmhmxsrp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2frgpptyx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gt2yqloabtx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gt2dqcjukyj.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gt2bdbglvjv.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gt2xszrhcln.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gt2srxzsqge.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2jdrteogx.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2wrtocinj.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rckwqnfj.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gt2gtehoaxz.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gt2cwqvfetd.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpbrompq.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2ythluxrk.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gt2sgparbgb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gt2olmgeceb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gt2irstpiho.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gt2zgxzfssv.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2yhfxarpw.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gt2czjjntmz.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gt2tsdsdrnm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gt2gealemfp.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gt2xdetuhzb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gt2jknmwowq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2qaaqiify.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofsbonwm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkqftqme.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2nxhwvnvb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gt2mpacvcwd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2blygnzzc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2yveazfbv.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxgxsojp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2pwoaqpxe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2rfuvrlzp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2ykzetbsw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2iqkricka.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gt2xbptfghl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtckuidy.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2hgwijjqz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gt2bmwoyznh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2hoyspajo.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gt2skmwesyo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nittgcck.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gt2sqzrtzje.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnolcpao.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2hzzyhjpt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2sjrlprbm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpxdrire.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gimhkxza.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2fzhoaanx.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2kmpucdqg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2mcrfrwjw.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gt2uobdbzoo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gt2wqiqybog.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hzdbtoyf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ufmuxabp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2wihptvuj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2ejnxixbm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gt2hsixrzgf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2vnuivqyy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gt2bwwakigw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2coleikfj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gt2xhphixjo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2fbwnwjjq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2otkyxqbk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2qbdszrhh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gt2bgcwknks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gt2yqwumaxn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2xqjoffnc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2zzheywhv.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2rfqmrzur.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2hewygwmj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2nbakdvzx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvfzvdxq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtcclssq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gt2akkrchjf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojqxlgnv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2lxwotwjv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gt2wjtztcag.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2bwyszqbr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trwlrbrs.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2vfzsejzt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2uxrrnhut.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2exztmbut.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2srbwrxdt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gt2ftprronh.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2rhbucvnl.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbulbtul.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gt2kzyteedk.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2kljnpkyk.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thbwumrc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2minfdgtm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2gkocpilb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2yedebokz.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2wtsthyto.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2nmhrnkmd.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2vbvupbpy.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2enccgksv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2scicvqwx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2icaqvohq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2ilbbsoir.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqdafbbz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2ypncylew.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kykhhulg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gt2lfoatiuj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2kcgiyjkp.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2rjznsoui.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gt2qhbautej.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2rbedmgvz.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nexxibci.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wazlljia.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2svwnmflr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2yzstsdoh.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gt2vcyqviqu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mehilxso.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfizrora.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ohqavqvx.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrvxdpbg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2salyhunv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2dwnydsyv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2anmksqkh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2krrcpwnw.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2vcmgspom.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gt2cjmwesye.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gt2evflrulc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aruhxztr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2wtthphip.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyoprnp.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2kotallqy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gt2kneppqgg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2sxxhniyb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2gieekmjb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2fgrhlkfu.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gt2xrdwzssq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2evimdieo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gt2qxxcfcjp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2szmtnwxv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2grrccupz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2luvvzckx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gt2hvorxocv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pxhmrety.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gt2vzikxwfu.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2dtpgwjvi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gt2gvhildvz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gt2vutapokv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gt2ghzzopee.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gt2rjjefgur.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2gcoeomef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2npeiheft.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gt2mzdhrasz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gt2videxqiw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2gtqadxqn.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gt2helvxyzi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kbpyibsl.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2bmoopmqi.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2errunyhq.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2lvoltrox.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2ucnniwgi.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yxygcxsz.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2jlkjivzb.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2hprvxepx.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofgxsnoi.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2hxpfrfvj.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qidvoyhn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gt2pwuyggvd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2cbyczhqj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eplgnevd.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2yzjrnsyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2alihckuu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gt2gpyopbor.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2poqyypnx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2eplmouqa.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gt2tiykjmyx.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtygwicu.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2wbgljvdx.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2vmrlpkrh.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2irjgoztf.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gt2ouzilcjc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2gihcospw.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2carxfztl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2koqjiiug.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gt2pfprjjxj.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2wckhqgrn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdsyetxi.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2rozlzdkl.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2bvkpdumc.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ejytbvra.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2maqudwui.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2rzlafcat.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2adlsdoez.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gt2qjdygfrh.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2mvgrdsro.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2wccxvaht.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2oprknmzs.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2xqbpjmpa.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2vqsrxyye.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gt2awqgxgdr.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gt2cnuaqnea.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gt2uosiivqk.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2mviaqntq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2pjnfdupm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2isdumjoa.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2ighfwpwp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2xngotwxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2blsxqdva.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2jmydprvh.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqwmxuhv.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2jigvveam.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gt2xaaoalzk.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2gndxqkef.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gt2yopjjtnd.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2nyrkarud.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2nwsrpbzd.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2qicvwgvg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrgbdtef.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntsyezfu.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2pmdnvtxy.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gt2jmskcity.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gt2decpuvbx.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyieqldn.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2biaadcmd.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2lwzpuprv.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2ncwpyaza.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gt2uxxjofcq.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2nzgneyfy.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ebczhsjd.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gt2rocabxer.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2gevanytb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gt2jtkkopfw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wafvsvdo.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sbcxxhnw.html


<!-- 参考信息 -->