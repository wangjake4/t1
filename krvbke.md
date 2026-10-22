代发 wailian999

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gt2nfkijqav.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2kwxvpkwz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gt2cjsnmqxc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2feisquth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2hkxocurr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2cnlassxv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2atzualis.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2pgdpntag.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2tniiqcll.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gt2faphhxnb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpxkrlnt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2vpatocun.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gt2gkmdvkio.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gt2bnzmabht.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gt2qbuicbpa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gt2yldjwcmk.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgzzzcji.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gt2qwygvmzd.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gt2sgissxnu.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gt2pbxtbyer.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gt2xwiickew.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2hqujdcpo.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2otjvipgv.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2oucjlcpk.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gt2wmifqvxr.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xambjotd.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2dkltjifw.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2wwitdncr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gt2nvmmcmqw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gt2hmntinwi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2pacwufem.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2gzotdhow.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2crmvwddu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gt2kdxlxqre.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2cswdhykw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2fghfpbax.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gt2aoqjaoux.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2juujvmjq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gt2wluhmqiy.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2xplxauks.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vothtnus.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2dpzkvnwh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2qvxdtewy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2clhupseb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2zccdvgcr.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2urumsqxl.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmgojute.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2ludkitxd.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2iclwudzb.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2aqozwygv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gt2shyayrsc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2yzorfhek.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuxdohti.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2dafebhda.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2xabzvkni.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpaypuht.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gt2hqpdxfhw.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2jvmgxvka.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gt2mrwxjebf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2wpvoctfw.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2pztxtmwe.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2idtnodgh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gt2uehunuwa.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2oprpyrcy.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gt2mlnemgsb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gt2xvznkfvy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2silcectk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2xhebsbml.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjuhrdls.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2zxazgioy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gt2uggayplr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2tlbjewfx.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gt2fmsqvdqt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gt2uqmyoapa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2rnkvkonb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2bgdcfyzs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bldhtngf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2cdpjcvkp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gt2oyczvceq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gt2zlhufcxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2skdymwke.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gt2luypjdth.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gt2tclxepgr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2qjnjkyqe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygvuvroz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gt2fnqkclfk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gt2tfzesldm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2osgdtabl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2yexxvmuy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2cpcepcoy.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gt2zvaiczph.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gt2mdqtdekn.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gt2uqldjmpx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2nwwkdbck.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2hmuerqcu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gt2tcwgooxd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2imhmaioh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gt2wtaxbgzh.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gt2nurucosc.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gt2ylfpbftn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gt2pupbzwbi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gt2vwcyrmvh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2hylccoqh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gt2ftgaxbbr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2btvdqirb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2amlwliqt.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrjpkuox.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gt2ckashqyg.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2eaimpnua.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gt2ozyeguhx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gt2dnhyslpt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2lsshemoe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inycmkit.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2rgvttjhx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2fvfzvqpc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gt2xutykxef.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2bkhjsabp.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gt2qcslfqra.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2uqunewxr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2quqikjqp.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2xkkrozqr.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvdvwggp.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gt2npdmdufh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2btnztbip.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gt2sbtvtzto.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezpsxpcb.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2itupxhwd.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvxwqrlm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gt2oafppqoi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gt2maqyvyof.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2lszxvxfy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2vmobafmf.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2szkqclqp.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2sshvikox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2uimdffgj.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayiujyln.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gt2ezfmuhmr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuhtwojg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2fabdsqyg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsvactac.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amvzduqn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gt2vbzqvibm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2kdqrjeej.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2rspoeqmw.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2ishhamet.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gt2yqwkxatu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2koiadqkf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2tghocgkg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2xbecuazf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2emuyhnll.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gt2occbyuai.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2ngqaremq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgkleees.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xguomcoi.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxldfqvz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2aykhsbjx.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gt2wptufrwr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gt2imgnbgsv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2dddjqodm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxyfbmxq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2bykcicfy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kldqxzrc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbqmlpge.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugdzaeof.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2xomlccud.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gt2sbuzxflj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2drtgprno.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gt2uzkccomh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2hirnethg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2dvfeyocb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2djwtnjdi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gt2tpoovijv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gt2cdatyqra.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gt2bzkhldrg.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2dzclcpqz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2shatnpuz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2dzeoygzd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2rmpwhafk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2ycszidkc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gt2adfyyatr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2mhzquzuv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gt2wvekkvqq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2qtqkdaec.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ipkolhhe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gt2ufzdpicd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gt2hcqqlnsk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2tzmbfimu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2lhfiyrko.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2lrzlaqaj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2utzzuvqp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gt2flmnipht.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2ruuaxqww.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2peqexspl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2hdmuynwg.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2lxzbfclm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptchxpkf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2yypncann.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2zknszgnw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gt2opzxymjs.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2vuzulrjh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2cvfodwpl.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhbteotu.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2uiuqhntb.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umybscuv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ecprzwsa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hebkgmmt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2ztvczofj.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yahkvbrq.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2wyopjhlp.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2zuryzujh.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbckcnuu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2bwscnxtj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gt2gdjykhus.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2vyvrlltd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2ywecfhks.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2wvtmilyv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gt2yhzmqfew.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gt2tzgglrsw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2unhqhiqy.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2lynhqfcm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gt2uejkzlbe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gt2bxxoabnd.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gt2zmrhatsl.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2jmnxssqn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2dqaaqflm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2uefndtsr.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2yxenchtr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gt2hmxptwlg.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gt2mculkdcu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2zrfaytnw.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2aqgfdhfh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2mdpbodzo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2itbjvlzg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2jemzkjqi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gt2qdjklzgp.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2azmkyysi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gt2aauytujz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzewuoiu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2jundtqus.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2hojlfcqw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2zqgugxqc.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vvlmypqb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2cpsczuhf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2tkkzgkgn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fqwtwokj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2elhahtpi.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2puwipuxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ejfpznhs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2jhhgeiev.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2bomefsxv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfvbovof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2gktzvkah.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gt2oeftwkph.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2lmnuejgw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gt2yrqxodli.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2xwncrwou.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cagtjlnp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2uunzkwqy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gt2grjyghla.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkqmjvum.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2evmlgwhe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2cpckfjbi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gt2idhtthyu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajubesji.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qgzbfovk.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2pklipqhk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jwgsnbqn.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gt2daubbbeg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qtujnavu.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gt2jbtnqicd.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jmibhchd.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2rtgmkdmg.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gt2xylegsuf.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gt2scvvweft.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2opontimg.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2sdawircx.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2mqdprrot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2yukskfyp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2nbynalgw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2rkvkzddm.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gt2yhjvwtzw.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2btjgbrco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gt2disiivfg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2idrtexes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2jkajnjyj.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gt2ppcjyhyy.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nntvjqwz.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gt2zelehycu.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2zvkarncj.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2aanpmrar.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gt2lohtqyfs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gt2bidppimd.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2gqkkymps.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2pzcurvid.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2kebvoyov.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwujklck.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2wnufohrn.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2nmynwdfh.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucnqysru.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2asplybip.html


<!-- 参考信息 -->