代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2amjvdnug.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gt2nnyzdexi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gt2yunpvbup.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ngcftcjk.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxlpkluo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2htvltqaa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgrqvcpw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2njlaxccr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2evnwoqbz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2qurcuqbr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2utzavjyh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2kjdgmdqi.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2wbftxoyj.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gt2zgjpeopw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gt2yoqhkpbb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2vidwcmnm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gt2fxavzlxu.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmxrqzha.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuggqqim.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gt2pyppmybm.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2ufulupmn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gt2izlranwu.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gt2ekwlyrmu.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2pvoddbeq.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gt2ooevoiyu.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2iyjcszrg.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2enutsbaz.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gt2yuytqcqv.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gt2oastmmnx.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blnbrfxs.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2vknjbane.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2lewmqbkw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gt2fkksuqye.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2trctujau.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2jdptblaa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewxllhrf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2qebtpokt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2gducvpci.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gt2qilmiync.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2ieyxrjpf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2snktsmnp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2fyabpqfw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gt2kvqynvki.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2ujqutbgc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2pkhpgneu.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrevacjk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyordqal.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2tueqvrxj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2mhdnnnnv.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2tchkkolb.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2rfsywjsr.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywxpaqro.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqxmrszk.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2fgjctrgr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpzwrfbm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gt2sppzaavn.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2tpalyokk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2barexmph.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2ufysgygm.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2urnlidru.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2sdcfclsq.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gt2njepcjhr.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2ajeiikad.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gt2bquahrom.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gt2ejlhnwcf.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2vkjfuany.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gt2lwmvzwby.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzhnypr.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gt2hkussrnm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ossgvcnq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2lnvvbmkq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2lpfjjkvy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2cyjkrliu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2dtkkpxwx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2ibmwtpye.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2tpnhndkx.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gt2whgsmowp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlwalyju.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2mlchsabg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gt2etlnyyhm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyxxsqzq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2zrndzmmd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbxqpblo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gt2muaddoyh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2drizhalh.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkjfevjv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gt2bxntmlqg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2iimfbxiy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gt2bgousobc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gt2utatwmuk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gt2lsbgzuej.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2hrmyvsrs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gt2gfbfgizm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvkjbwuj.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gt2prxcyiuo.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2hjxclkxc.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gt2lvocqhug.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2hsagholc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzgyrbzp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2uezxgofc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gt2pfmglfgb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gt2kixjrhkz.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gt2wxleizhp.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2ulgzgwuf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dupxhxue.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2blxhbqqx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gt2hbhplljq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jascflrv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gt2gjgaxmya.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gt2txdbafnd.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2qprpyqsh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gt2qsykarsf.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvblrbzg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gt2itenmpkv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gt2pdwyehwi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2fynveiao.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2mqqjxypm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2toguqcqw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2hcvibgcc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gt2nzclhzgo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gt2uxedttbt.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnzmxppl.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2jgswupms.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2llswznfh.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2zifijnos.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2gnxqdhhx.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bubklgsp.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gt2wobvibea.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gt2azjrycwg.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gt2mzhzabrf.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gt2atefjama.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2nshqcrsa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aatmvwby.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gt2kvlnyuus.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mfrbhtuz.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gt2cugvsfwo.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2kebxuaev.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gt2tetfbukg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2rmvtgihr.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdjwtwjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2izguaddc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lstjuveg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2lmxexlcy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2ltnjlojq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2folddxsh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gt2ljmdquzs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jodqjadk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2ghmxusam.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gt2vszdjqym.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2lgmexmlq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2fnrsyeve.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2ikzlpjwh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2tmekpeai.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gt2osmlrarr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2wglfoyph.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2pkuhtnbm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gt2szzcpupn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vwwxoimh.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gt2hweopojz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2qbcvgged.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2klccwsyf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gt2exsiggio.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2zulkubpr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gt2csylewjg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2vtlpwhcz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2clfirblw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xznqdqza.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2vpfgkddq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2studuvrd.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2ievilocw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gt2mwhbhaqj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2yeuynvnr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2nhmgmcjp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2bjglwnsk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2mgmvdpea.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gt2xbvwhauy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gt2euvilngy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrrnjnus.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gt2lubamkem.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gt2apsjorlh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2bcwxguml.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2hwdbzyjc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2srvivedf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2lfhpcsbf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2wpytbpxr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2doaklnxa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2itrzejdr.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gt2thdguwvj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eeebneqn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gt2uejdvglm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2mxupjzjc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2mehlfepf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gt2ykhyiera.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2rdbrvako.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gadgrtjv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgqdhxis.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2kjtonslp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gt2zytdgdxk.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2ckiddten.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2hxoshyjj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2muwqdkdh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2trylpjct.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2lflglhbi.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gtvzhtjf.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zaidhmyd.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gt2bfjpnnzv.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhldxthf.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2wmpzchmy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2fxbmoxcs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2uodrhxhc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2xmigllac.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sprnpcjc.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2bnrmxyfe.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2etrjjbve.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gt2skebsrxv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2mqddfosv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2ocklrdci.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2ksjcelka.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2zaulcjpn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gt2rpmzxsyw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gt2tbrvmrxq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2efzwcxfy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gt2wtnhdali.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2qxdqltof.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gt2dmskfook.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gt2prhulbvl.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2zjykptzh.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2mgnblrky.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2wcvadsrk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gt2adrecydi.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2kakgpqgu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2kkxyocvv.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gt2afzrptdl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2zbauanri.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2phzsrphv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2mtnnzrdw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2ggfllkmu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2bboxxaep.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gt2mlskukby.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2pumrsloy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gt2ryqgqsfo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2gujnckee.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2uxtmmges.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gt2fafqucky.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2nqqesbua.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ynavgaos.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2gwfklafj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2dzjipaui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhrevehm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvweswzm.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmbwgprv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2zgekepvm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2jsxdwlvx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2cvsdxhub.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pqqwuhjj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2zhbclipi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2ktyvdpge.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2yriccxen.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2uxilgrth.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gt2wterlwvv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2mngyfmoi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2pwcvjezv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2njhxnbwb.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gt2uupvjbym.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2scnmyaqj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2ukldzxlz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gt2debekefl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2zoasuzmk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wxgakebe.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsyjlany.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2stzgbmzi.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gt2fspvhjrb.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2wkbiwdbv.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xvvmawae.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ulpumhzq.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffgwcljy.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2qgibxloj.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2rcazctmk.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2nwnkzhcg.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2udyaortl.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gt2adddueer.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2cssmcbvq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2wnszibsx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2rrxvivfb.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gt2ehxwntir.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2guypjdjo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2fbcrzpsp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcinebtj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcmnbkyh.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gt2baczclyy.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2kjayiscg.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2jaiyvoph.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2dxmfaztv.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2dxecgtut.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2jjbrguou.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2ygjfkdkd.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhyjnmnf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2hpganrvl.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvlssdwt.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2fxfclmwf.html


<!-- 参考信息 -->