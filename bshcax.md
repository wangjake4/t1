代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2qirklves.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gt2tbduxucs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhqarajh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2fuokwpho.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gt2orofsfcw.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gt2haavidno.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gt2pbtnbxvk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gt2dzkgyduu.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gt2hymjzlrx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gt2gwjcbdpv.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gt2dxqowjey.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gt2yenzvhik.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gt2sdmpywwr.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2sowasxbo.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2lrnkqryd.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2kmuwuujd.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gt2apvwulda.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2trgmyeqv.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2etxrzmlw.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2bfiryupx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqnscaqw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gt2fxvwwfeq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2lmoynlxo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2rlmsoiii.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2qqaevveu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gt2mnfgetvt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gt2srrftzwc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2cealfrdd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gt2auiyempb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2bzrloujp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gt2laaeukvw.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2hoqccdli.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2grgedfok.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fiqhkbnr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2wzavgtti.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsponzry.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gt2mckaldiy.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2scjecawk.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2ruqcwjvr.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2bgpjnvnt.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2ondvmegh.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymefbcyu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gt2igfojcmv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gt2tqwozicb.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2sluzczin.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2jvikudwd.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gt2vupfftkh.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2adfztoaq.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gt2gfnjdywo.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjoxqxzs.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2fuxsdszo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gt2jfdwdhts.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gt2cltvdmcd.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gt2xamtaypi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2gnpgtbot.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gt2xhgbqbqp.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nopkupql.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ugpdoxgt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2hfbypjjw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2puzzvdhu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2slaguarc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gt2yzhiotck.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gt2ofessyxw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkdpmrwl.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gt2ilziqwtf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gt2dzwdasvi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gt2nhdujsad.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2jwsmzagj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2brpiozsr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2srjurpkc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gt2rwayxryb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcuviihs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2dpjpzppw.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gt2iiwvhbfl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2dgvhksia.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2sybcntcm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpyxshkx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gt2bfoycbne.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gt2wqhsssal.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jthbqgku.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gt2qmmfdmxc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gt2dswlexpd.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gt2pbxwlpxz.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2mopgiher.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gt2gbrbqryf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2bgrurewt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2qetmdmfj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2vbucesnx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2dpglvpqk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2ihsphmaq.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2wzgrmdxm.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gt2idfulwzt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gt2rvobsecy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gt2jqkdtttv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2gocomaxs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2lcajkysy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gt2anplixoc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gt2ujczkjdu.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gt2rvkvxwst.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxipkqzv.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gt2bsbhroub.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gt2edqtjfug.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2vaqrjjum.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2wxofivhz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2iknbhakb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjkcgqzl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2ewmmlouc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcqvkmtt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2keuiclrr.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvbfslye.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gt2sncoxvdw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2jwlbjnli.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2ztinegmm.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2gstxnbkq.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gt2shxlhksa.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gt2ijtwixbt.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gt2upxepapv.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmddcmcr.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gt2qpetscrn.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gt2pcpgdzxl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gt2vuiqeoqi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hoqaapxd.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lmzhdosv.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qwtnldia.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gt2mqmhndxt.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gt2aoqoxaaa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2hwgqyntv.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gt2fxjnmqwb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gt2okihcnnk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkpywulw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2swhnycke.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlhrrahe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2rhytzidh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gt2lkidofvq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2nbhmgmzu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttujltwz.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2lhjzjjky.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gt2lmrlpnft.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2vbjrqmyi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2jrzbcwyp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2vcropcbx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2avfexxhx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftdfzqll.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2yjrlfvtc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gt2xbeplhbk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2yabvwmut.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2yfiovrqw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ekxidzks.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gt2xjoqxtxd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gt2gvqhlfdb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2tcjvifir.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gt2pwzvfhbu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2bwpgnive.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebnwnxwt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gt2tuwtrkxs.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2vabprrjb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2oiqumpmh.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gt2pbygarxf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gt2slefwzbx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtfaqdrl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2amntbwqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2xepjwmib.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2uwudumxl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgmhrorq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gt2uvzvrowf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuupslws.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gt2dokabhzf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2calmbzlm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2nzkcmjoj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2cjljzsyc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zitcsasr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2aqevohlq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gt2gonhnmgv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2glfnirif.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjwgjbuh.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gt2lghdichp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2sbfpesfp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gt2mdqghthm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2pobgnhfh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2gscumpro.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gt2dwisnoyz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2katcwmiw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gt2jngshjfx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2yjaeoccj.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gt2utyboemz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2rvtknjtz.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtwhybpu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2vpeuvvjg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2olhysnvd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2aduizzxn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2kviprjie.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2tzjgqgeu.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2kowuoawg.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2jqzdvfzk.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2pweazdwe.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ndutibud.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luspjodc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2zcgumqyt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2uhpkcndp.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rokqwcxq.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vphbwwfw.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2jsasxdey.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gt2wqbuczzc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2mqzshedu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqnokdzp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2zbjgwtnw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2otpqliwd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2exdbyvso.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gt2idthwtmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2gznasoim.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2kojokfzl.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2bdwgadbm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gt2ezmaqvdn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gt2nhaxitfm.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2ozsmaodw.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2eufguhhy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2kwtyfevk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gt2giqctlqq.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gt2zdfrzprm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2ctczlagl.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gt2llystdcd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bojyuqbp.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2zcsztcdv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2quvojbnf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2awgxwgpn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2kebbotse.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gt2ynhimvur.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkvymrkp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gt2jrxxexxw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfbgvxkn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ptqdutfz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2qcywzztk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2xumzfrsq.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ocgpegmq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gt2burafztg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ntulmjyj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2fbygtcyx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2duphclpr.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gt2bqtpjkot.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2wfmqzise.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2xodcsskd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ctauemdb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ggusnvzx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2wzutowpf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2kxfcplqk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2cbuqzzix.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2dszhynsc.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2ftqlaiwd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2oezirtdq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gt2rccumwnx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gt2zlntdmal.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gt2hyvfofmh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gt2lporntqh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2lcwkjedx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gt2wlihevue.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2pzntesbf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jzcyuqql.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2sdnlkanv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nrzjgpjx.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2bczvkabw.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gt2qufifuop.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2sksaejhx.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2xnedtcvf.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gt2uckavqsi.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhnexlwu.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2qpbwlcrn.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2xgwgnjgt.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2rhntcwcb.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2lnwbxsuz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2ocyorfri.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gt2veqrcqvi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2xipjjzvu.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcpgpikq.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2kgtmzoio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yslsweyl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gt2okfeflbn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qudijvne.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2hszlaibg.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2yxfnvmlc.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2zegraljf.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2ebqcddcv.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2zlpqslxj.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lljnmpnv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gt2uibjtwws.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uymhasjs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2azsvxkqa.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gt2deftxdfj.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2gygztfww.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2qhviuxbr.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2sbfjdomc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2lvcssjyn.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qencvoia.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykuadytc.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2vngvakhh.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2dfxbgbtr.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2guveqyol.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2vzzqqmal.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2nntrxkqh.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcshfwrr.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2mhwhufrd.html


<!-- 参考信息 -->