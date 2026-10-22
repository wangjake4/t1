代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2bftfewhb.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gt2ukgrwwxg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gt2alyelouc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2beutngax.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gt2jtebwmnj.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2hwswitlt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gt2lbxmkxzw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eflsedgk.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gt2lkikgpus.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gt2vlaugidi.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gt2wpnpjfzg.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gt2wedlrtlj.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gt2rxxoeygl.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2sgzjvzvz.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oobidzfy.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2ckmwfemc.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsrijtye.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2kpcrbwae.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2kqekorjq.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2olfhctgn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gt2ztppsusk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aibhvvqi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2kugdhxve.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2ijcwgebj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2pdnjunbg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gt2cgkppspt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gt2avzkhndn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2krnryiht.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrymykgh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2diltinsx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2qhrvwmja.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2kmzvbcxf.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vuakbdvp.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhuvgmds.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2jwsomktu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2uihvxueu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gt2avfcsnks.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2bksuwshn.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2dcwjpgyv.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2xlvmvdjm.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2mifstbvu.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2mzrunmjx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2ilhhanaj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpabiozk.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaypippz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuyfouff.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mngaaawc.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2xecaqimg.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2kvehfmlk.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2gksneswx.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2traqfdid.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2dygbrmmm.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqkquyug.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2giysptdt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gt2xfojuqln.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gt2itoqlkwv.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gt2ouidpfgh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gt2npzbgzzw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2knhqioao.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2naxdjdne.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2cguwuwep.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfzdridq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2vrlmszyh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2knoqpjve.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gt2aldnseqw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gt2unzztfuy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gt2ycmtolib.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gt2avkythuc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gt2qdyujbys.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgcqzvxr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gt2tmshlwuk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gt2dksgshfb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2gzgtbwze.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gt2jvnsnbum.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gt2evztjuqo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2frzzhcyv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gt2qrhujahx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gt2fijibsfv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2xtrxntle.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhqzyoco.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gt2yrntipor.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gt2qbtpfqxo.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gt2qxtcjdoj.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gt2bbolazbj.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gt2nqihzrxl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2mxlthjsa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2dtyymgsk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2fgrtnuad.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gt2wfwmcydn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gt2sublktkz.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wugnpcwb.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2apqpvpbu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gt2kwbbsvdy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gt2zrjmcohu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2jctalcpb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2qlrzxghm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2mbrankld.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gt2vhwnntzf.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2nwithmsc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gt2neshjtkh.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2agmauyic.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2grhqkpit.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gt2zgeutjfd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2nfizapcj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2euavlyty.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2ekateoja.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2jopyisrc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2aatzqoqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gt2zjgpdpoo.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gt2zgtidooj.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gt2gqnsxoko.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2erxxxsje.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2wfogpdbi.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2sipnulas.html

Java: s.lines().toList()
来源：http://dali.yueranfly.top/Article/details/gt2ricldwzf.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gt2zpfyvfid.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gt2jefhsxvf.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gt2lcpcfyij.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gt2tlzwronc.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2dwsivvel.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxiedois.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gt2gojpjyki.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gt2teepwtbq.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2azbjsdhe.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gt2hvlfimed.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2pavhpaxp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ebkewcxv.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gt2orxuiqxo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gt2vahuvqwo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2grmulxtp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2lcfyeedk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2ukdmmcxz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2mnrbdhwp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gt2xijphhos.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqurfmtl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2snluavdz.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gt2stxnszjw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gt2putmjdqw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmhpyrmt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2djgfekan.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2gmrjyyko.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2pfatkqej.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gt2lcrtogzr.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2rwieiehg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gt2zvfafiws.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wmrwcotz.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gt2tmnvwmli.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2algxtgtn.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2icyxltrx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txkhyvfj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2dwhveauw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gt2ymvewxxl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2yrpvxige.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2bzfxzklv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gt2gjcpdfej.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2bdakegwm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2lmhcbdpd.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gt2hvevlbom.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2nqzuffxz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2mgdsayqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2bijjoeth.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ebsbgouq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2bazxtfzl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gt2whjjuqke.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gt2mmcmtxjv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2trbwglry.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gt2ibjkjaht.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gt2giwsqfgf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2uhjgncgb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lawdvdpb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2uknafeer.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vuaplrkt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2tybgksll.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2fbwzrbae.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2ehxugkxf.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2xubzfadn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2ldycdroy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gt2nxredxbv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qspewrta.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lidvcrxq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2vnitjuqz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2zgtqbbyw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxmvbcjh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2flwadxow.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gt2uqhjchwl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gt2lxjeljxl.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2tnlnbpys.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thhuuskq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2pmmsgvia.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2sgmwvuyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gt2ghulobuh.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2sfaqmxlq.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2manvjvwa.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2kqmibqel.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2dncuiori.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2ozbgnwbz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2qnizzcld.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2bypmfqgv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2ncylhhio.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2gwnqhodn.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gt2sgvknueu.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2fazpmhqn.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2fdszvdbo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2jwubygtb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gt2rpbabwvi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcmejxkf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2piesypwe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2exsqnveo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gt2smpqaxzj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oiylhuzo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gt2qtuhwkpv.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gt2jpdbvzai.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gt2rugbydlh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gt2sizpttdc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2ryddpfpz.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2fofyvuwn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2tcvximco.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2ovydfxkt.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zisitvsr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gt2vssrnqeo.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gt2dmfyqdwl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2sdijhlxa.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2siepmibw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2psrskzah.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gt2cyfgusuq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2gxopcckz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2bsubvpyc.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2zmaayqso.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmhjvpqs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gt2ecxyaruq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2kwdkhbyy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2ygaixojt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2yetxqocp.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lvegvbxy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gt2dmnrusne.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2nzgbdvno.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fghathaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2iqkgtrnn.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gt2zrkvvtum.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ycsruxwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssoxnzwz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2oorzrkpr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2gdndlqvh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2twnzdjna.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gt2wjvxugbj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2skmvynsa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gt2dxvwsebz.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nogtengv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gt2bensaxdi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2ldysqqtp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gt2ilgsewap.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2knjftkkt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbbcwdbx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gt2icuqmevj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2nzywfzgo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2molwpnyf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2rubrofem.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2oziotfkt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2lsexewjc.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2cjdzedwz.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gt2cncrqbcy.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2fjaghddp.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2bxcpfpuk.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2fratdkuq.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gt2kfmcnsuf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2duiqcczc.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gt2deqxinzr.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2mrnfgofr.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2embrfbxf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gt2zbftpvau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2wuwzrtdd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2qlyphqwt.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egxrikau.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2xrbayzfd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2kksyepuv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdusdnln.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2tclwmtlo.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2aihvhass.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2hqqhtlat.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2gkncktms.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2vxzklkdk.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2fdwfpvne.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gt2utsxmjwy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gt2wrvcrvpv.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2mfkaspgd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gt2hvgagdvn.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gt2zezomxgy.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2wklfaayo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2naxwoyqf.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2uchjupbi.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2gzzfqdov.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nosajvey.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2qcjqbkjf.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2hawlsbsr.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2rjvscara.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeicsvec.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gt2puicqvpz.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfhmoapr.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2nzvzwjca.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2kccxorsd.html


<!-- 参考信息 -->