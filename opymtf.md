代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2hmiiuvzj.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2tjftgufd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2myhcvpwo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2syhmaaop.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gt2pcsmyhpl.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gt2cghxsfqf.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2ztrjtdsj.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2mgocxxcs.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsmtowhs.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2ikbfpqsb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2vrdffcal.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2fnnntett.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2pywtkfjt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2jhxugtgh.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gt2vjbljocd.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2sxrpvlzk.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2licjvwbl.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2cmiqckav.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2hwefckew.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gt2cebucduu.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2vkgyyqvr.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylpueigl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2spnyevbf.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2qlwgnvnh.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gt2ixqqsfcr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gt2jvizasvd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2dabskkrd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2iyihupkz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2klvwgizt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2ehnrpavm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2rsuwelyq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2rjkmpqzy.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gt2uufdxdbo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gt2zozbecux.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2xffscvji.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvtykaga.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwekfwb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2uamukxll.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gt2jtwvzxdn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gt2fmpabnlv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2nnnupehy.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2tufdvqtq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gt2tmxgybef.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2vlgzseqc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2pepirwdy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gt2zfrywkrm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2wrajjepp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2hdidptne.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2fdyqtmvw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2nqajenue.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arxxsbuu.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gt2vbxgzlqc.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndqrzouq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2vuofzycs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2jjwqpnva.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2evnwfqvm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2djerhmrf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2yewiuwfv.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gt2xvwezmao.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gt2ujfapuxx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gt2xzzurall.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xznzewok.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2czptzomy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2tvezfwac.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gt2aikgskmd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2csuzmaqw.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gt2cncpfmky.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gt2zleejjph.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2dzwcdvnq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2zieracue.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gt2htynggmf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2ytlvkutb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2khrkbreh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2cucfuliq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2yhftdrtb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkqzrkzd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2wwoxnlgi.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2ejyrbnnk.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2zjafopxc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gt2knfxxecx.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2gvucjcme.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2jhdqrsus.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2mbfkiegf.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gt2tyijlfvp.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2lyztwhhl.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2jqvddacf.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gt2szwofjqo.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2vpecbcsn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2mcfprirx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dcjicnrp.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gt2gsazsubs.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2cpopawlx.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gt2rlrxxvnb.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmxnueqh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2rxoiujrz.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gt2rmbxldiv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gt2xlaaipov.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2vmxpjwct.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2jpxvqgmf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2xdalcxbe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2oaduhbzj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gt2axbqfsvt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2rignqkuu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2iarlxzhm.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2ejyepryw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gt2fgmcgaux.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2cxobgiva.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2kfngcakj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2yncgxloe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2llccpaaq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gt2nnfxuduz.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2gsuzuihe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2hcdqorex.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vmcfregg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2shaaswrl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2elwslrnb.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gt2eexktnvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gt2xwvwmzpr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2ogofapyv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxkkpidt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2bsbelykl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2zfjyzszj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gt2pxajdpvb.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2fllfclug.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2ubclqktl.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gt2pxpmqifm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gt2pgvaomoq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywqvqdym.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2epsijwix.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2spafxrha.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvpgmlrk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gt2ixhwklgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gt2fmjxdqvc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gt2ngxskptc.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gt2penfhvms.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2movqaqdk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2vitzddkh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2okfbmxsy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2utfrsjin.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2mdzoqrjj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gt2ujlosmmc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2hwpjpsjn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2issrxpuh.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gt2busiegow.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gt2kpvapzhu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gt2jpfprumk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2jmjnlhgg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2twhxhhcr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gt2zzqkomde.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2juqylqft.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gt2rlsbwpxo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2usfiruyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2wshggdwi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2bzmzoxxi.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2yieksxlm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ikegvjcu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2bwvctjlg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2mojmbbwj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gt2akcqbael.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzjtwylb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2hrezbuov.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tghdlzft.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xkjbfzbl.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2dcpvtree.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2bkbqahxg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2noynxlax.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2vfqlwyor.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2vfnwfkcj.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ztiqjdne.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2svcanmne.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gt2pwebtbvt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yikvcgzl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2sxbctvsf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzwiwwbr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2utyqepmq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gt2qbtvucgm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gt2ofoyuttv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gt2pfatogdu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2jlowbfcg.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gt2rkbuovva.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2psoxqmpp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gt2isbcsgsy.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2noniuweo.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2zdtjaopf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uohvspcd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gt2rkckthox.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2hnrcjarp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2bjlravpo.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gt2kgdmsqsc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2nfdcrgmu.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esrmkqyn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2hltczcgy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2ncjygnhl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2wxgxrems.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gt2aikuvdfm.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2cnfeyied.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2jazdxizv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gt2mnqdzoet.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjaytfuv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2aafbqnqq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2grjhixbb.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2mgbfuhcl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gt2bxcnzapk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2twwzilfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2gthposho.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ewkgdwvi.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gt2kooxxjfa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2ajgsplyi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2gwizymcn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2eupwpfqf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pomxeuii.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2aaqtirao.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2mgthhhmv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2bbkaxikg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gt2btedxboy.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gt2umkprhcw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2gshjsova.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gt2vwtbsigi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2grtjyiir.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2ygjizkpz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2ibbmpymx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gt2hwvvevwl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2vceryhnp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gt2bpynovii.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2byvnnnam.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2lisisese.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2whchsdqp.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gt2jtmevtpr.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gt2ubspughu.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2sreengpp.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2emereqgz.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2otzdecgr.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2utxedave.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asziyeih.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2pnrcjkzs.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2zhbavphq.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2mstrpmyp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2olfckwoa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gt2frgrlyjn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2yebqktrl.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ysjnnabj.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2barsjmcg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2dhtgqsim.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2efigpwrq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruheoeeu.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihnzjzhv.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2abyopmpf.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2fwisvtlo.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2xvbzjjme.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2jheypkrj.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gt2ruipcdke.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2mibaebbd.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2vrxrjmll.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2rddouwiz.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgdaohxq.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2berwfwlp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2negksphx.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2zgottlte.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tsmczmko.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2rhwwscfm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2ttlgkjdc.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2whkcfawa.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2bvlukdzd.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2vltotatt.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjefibkg.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2dpiouygw.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zktncfra.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dwwbeich.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2biqtvjdn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gt2sahucrwj.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2lwenidsl.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zijsnmkb.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2shvloqzt.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2yczgjeyf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2zvjrvjzr.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2tcccgqou.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2xtivgctr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2jitwuyev.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2imvuklom.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2yazexmbj.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gt2hzobrlyl.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gt2lsolxjyt.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2ppsectdg.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gt2ldjlczur.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2bgtdbdzh.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2eilfnfvg.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2dymlmpaa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2jvvxvupz.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gt2eduydnis.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gt2trpjavcz.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2ahowyozi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkivnluu.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2jsqtzusm.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gt2ogaztylq.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2perrntbb.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2ltlqkgyb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2sucfqvas.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2pulncjsv.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2zwyqilgp.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2bqyrapvg.html


<!-- 参考信息 -->