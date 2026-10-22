代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtyjaxcolo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtsedfxkdp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtrkzjejxx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtmrdyvnqt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtpzzhaato.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gttleqkzzb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtfvlrpwgm.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtcaeeugan.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtofblyzdr.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtrmujsklj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gteqtmstsz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtxdgyybvh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsljwvmk.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtgvivjfyf.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtcpbtvhkk.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtufwguvof.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtiuduuzct.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtrqlhcbga.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtuaseljzq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtoqgyvuae.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtocryfgmi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gttbkoiidz.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gtbhorrvqy.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtbxnbjrzw.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtfenfklql.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtntdmcglb.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtzfmfgrcr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtwhpvntro.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtiruzmajk.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtntgkeowx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtpiplpgxe.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtvfdsmdjx.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtevcfnwdi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtuuqgelvf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtksoptqfb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtwbeaktam.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtyfyblwoq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtuvbrgkck.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gtkwnjoqbd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtraoqyypz.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtlnwmvrpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtqhkdszow.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gtdzlyxnrm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtyqzzebht.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gttzotzohp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtrpkbhfde.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtktiumyqx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzodrsuaq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtirbhqobd.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtkjwauubm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gteztslrwa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtkjonjmyf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtummqcqsp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gticyfbfkp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgplvzds.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtllgsubja.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdjuekks.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtaudileae.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtvztltmlu.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtsmfpdeue.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtpapshoud.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtoiknjhcr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtfiqqztob.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtfkdxbyyd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtblvljjdn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gttuobvhop.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtvxlbmmxd.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkynzjuu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtkvpkgygn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsbkhuezx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtfojzgebq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtgbriezyy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtzctvhnwo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtjvirpqlt.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtoipqyryg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gthavlacuw.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtuxrqbwks.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtckwaounn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gticmlyrmd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtjsvrrjnp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtzdjcetsr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtxqfxwcjc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtzvxtxblk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtvkvagkqp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtephtbbox.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtixnamerc.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtxqtxmiic.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtpiibwuge.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtrvqlttvl.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfdznzfa.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtsngpyyni.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtaunfcdby.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtjksklhwv.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtzkezzrpx.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtkwovvgnz.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtzbpturag.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtpuojsump.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtbqouyzhm.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gtqgrxvvsy.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtkgnhfbhx.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtuhqlfjvm.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirlyhjdc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtekxewkwt.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gthdievgbl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtdnalprdi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gttlsuxgdq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtojsosgaz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtbuvvjuzv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtvswbqepa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gtszdmfnkc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtlzikufrl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtwahlchzw.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtkdyhqshv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gttsjqrqqa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtfykxwxcg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtkzxvkzom.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gttaykljwa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtkibbjhey.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtntpdzhvd.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtviwscvym.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtwesqhqtf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjugujktw.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtihpwklbk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxqbnnedx.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtuvkwuzuw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtltkoecaz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gttrxhhlkj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtefcscyet.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtbwghhqwq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtamlhepam.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtfdpirexp.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkcypjqqs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtxgqikzii.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtopxtrgpt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gttvkdukeg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtalwwriqk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtsnyexeeq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtvnznitjv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtvciesnet.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtypyfigfa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtywogmrzq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmxbkoat.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtcldmnsxa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtnmejbxrx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtjzqadxdi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtgjeihppg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtsgdclahw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtwifvotyo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtsjzlredz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtjouceifq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtzjnatxln.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtocxlmzcf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtulunhvtf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtmrnrlytq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtjdgeldlb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtwjavjbxs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtaatofzfq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtotirqckr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtciiqeykl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtbyopazgj.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtuporwuva.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtsitjylpb.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtgdnhfyqb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtedkwngyq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjektqjvz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtweldynpu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtqrgqtynd.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgtskivjw.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtyuyigpfu.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlruvozgm.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjgeqckvm.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtqkzwlfmg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrgyphezq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtfzeebcey.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtiephergy.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgbpoepys.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkdattrdq.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtfdqusjsb.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtolbflczx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtnbhliitk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtyozrizhr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtaxfnjane.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtglortpag.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtsataiuug.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgitpywnm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtjfphhkap.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtloasepmr.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtqicsxqic.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gthqzbmpdl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtycasrzrr.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtqrrneirx.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtxwrrrgdi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtsrlnuybm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtafgqsyzl.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtvkfmeets.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtgfkstecq.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtuqdalhli.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gteqphgbiy.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtphlizthq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtjlsmnxxr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gthgpknxjt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtbxiuvzyo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtglhodfsc.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtfzshjjej.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gtklbanjay.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtgttomigm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdzcwvqwn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtnmpgtisn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtjkmtynfw.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtchmjguqz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtphsgjbbn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtugdmcgtd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcfgpexv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtksmnukxv.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gtvjiklphu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtrygkbjfl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtlroltqdw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtrzpizqga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtosfanzrz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gthaytrjsj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtrhxgswer.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcnquimpx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtzqmtgfxg.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtuyqwjwun.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtfxuyrisw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtwcexdagk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gttzyofehd.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtmeojmeba.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdahhnduw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gttpvgaiwl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gtzjthnzey.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtvrohufrp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttppgsarc.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gttteithxa.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdvolpovs.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtojrqevcn.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtsyfejonf.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gttgbuyevs.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtuqllbzof.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtukmpsbos.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtifseciwd.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtubbalppu.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtnbbsqtce.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtyhspwgdn.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtvyhksnqn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtjthofdkk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtqmdwaagj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtlhvyghyg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzchpnecj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtgpolkodg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtmuyfpcoh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtskcaxhes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtpjcxityi.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtmccfrgxo.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtyovuyqcs.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtofsooode.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtvikzufxv.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtesngmcbv.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtzvkvbuhf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtnqvxbijz.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtldivzynq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtwspfudsh.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtugbhuyzg.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtbnznaalz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtdubgjjje.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxgqkiiln.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkrhstmuj.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gthougvkae.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtvjvudaxk.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtozfxlkwi.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtddkpzdvk.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtmgunfcdy.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtaepbltup.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtfbeokjiv.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtwughaxfk.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwpaztklx.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtzdwucajh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtavcofvvs.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtayrdmexh.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtsjuinpjn.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtqqnnpbnd.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtdqeethav.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucymrwha.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtornvipxp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtlnvulsyd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtnttmhirg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtuddmxbmh.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqpatfhm.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtytgesrgj.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gttszabkfd.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtysrbhiij.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtukjywiqc.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtbycbwtus.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtygudniom.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gttakksfzw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtcjgjylhz.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtenwljokt.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtkokpaijg.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyvmcgag.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtrqswzdgk.html


<!-- 参考信息 -->