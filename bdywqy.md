代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2dgyzehni.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gt2yflczvgq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2mdyoubmg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2shesuvwr.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2vwmwlsgp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2nfkuhpit.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2cvdomlyy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2kxsppddd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2nlbrebye.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2trknmsyk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2biqsqcdj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2parykdci.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2nrmyketv.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gt2ewrqshbo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gt2flzprxdu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2rxgzijkt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gt2ondwamyv.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gt2hppltvpo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2cctehnsu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2lmakbpyr.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gt2ocalfceq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gt2duhpvibj.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2xokekpjw.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbmblmjp.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gt2tsadufid.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2hxoskunl.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2ijynzgjd.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gt2fwnvmlop.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfpugqpk.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2azxsfblw.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2qaubwkxi.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gt2hbqpelxy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gt2ognsafsr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2emjncrqc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2nlxkesjx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2wckxkcwi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2gvplbbit.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gt2zrookbdb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvlptbsh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2emtmxgwx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gt2vecfavqg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsvjzkkx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2owhiyyfj.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2ywcjivxx.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2lgkbmdyg.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2zznlwlyc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2anxixdcb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2rltdwqar.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvakwadh.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2vwiurbpr.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2mpoaqzru.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2zdhzqkrz.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2hyqrwqhw.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhuteahl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoyxlozy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2owskteyg.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2vofrqbqv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2lwoifgtu.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gt2oaivbist.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2rqnbpwnx.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gt2kmiuiqgg.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2ebtdvxrq.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gt2kqodxjap.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2roaobypw.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gt2sqmrspmk.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2nlgxxxyy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gt2qhujngru.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zakgxusg.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxhutegn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gt2yriocpcy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2sryowcge.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2swwweeqx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2bdutoudd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gt2dhsuxtwb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gt2avycsxpn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2lqauaavc.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2fymrbrcg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gt2bnvdyjca.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2cgqjmbvj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gt2fvpjrexf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2jcsznchu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2qpycjkro.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhqmnpdk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gt2ypkuueup.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2edatdzyk.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gt2gtkhrtha.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gt2kgcqgcac.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gt2spkyavzk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2dsvawkih.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2pdxidgpo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gt2pfcnbwnw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gt2fvdylgli.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2zdwscrbc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gt2gkgafpok.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gt2jwqxsiyu.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2qtpooekl.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gt2vdyigqrq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxybzzdu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2fkcbiira.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2nuoputni.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2bllitckw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gt2mowwbqvq.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gt2wesjcsph.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gt2uhronnst.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gt2qgcmbbcw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gt2fowmczad.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2zevtnvjj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2zvbybkab.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gt2keddyvoh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gt2pvgsyper.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gt2milzzbfa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gt2wainpveg.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gt2fqosxxiw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykdkndbz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqctjaao.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2xdjmrfcb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2mvniuove.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2gvefyoxz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2xiqdvpjf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gt2ezugkoln.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gt2jhyonqmp.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gt2kyjcuupq.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gt2dfjmuaoy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2duxcjsvo.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2versqynm.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2togdirxz.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gt2wvftlnsi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gt2cuggncfp.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2uvsairoy.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrjhcdxs.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gt2vtqnzyrd.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2dprpnigv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2xkyyjcxg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gt2hvuouyzw.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2idvzpwtg.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjnpxdye.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2bqybaoxc.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2hgahohcr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2xhwyvjje.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gt2yektehfe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gt2mbnamqzt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2euhepqvy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2vkqkhybn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2wblxoqhp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2vlhisvxf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gt2jtwwrsed.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdpnllnq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2thsrmrfc.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elydcrfc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gt2djiyxhdw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2npeozxwz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2mvllvwhj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2xytajfzk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2hbbskzbw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gt2glerwfva.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2njseglfy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gt2xkqokoxg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bpxakefd.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gt2pmmjalzw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2xpzvyvet.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2ubiqnmmh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2qulvlywq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ugjnjwjc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gt2wziokulg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2imujqrmh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2plcacqzi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gt2chqanqtq.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2firyczwy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ntqtfxrs.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gt2mzhovuhs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2ulrgzabe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2kmspflhp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2laqrkayp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2obrrvvdq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gt2tyeiirlc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gt2sctywsbt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2puelzwko.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gt2ubvhpakg.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gt2ovvvgdeo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gt2axociqgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sczoelxt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcafrezd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2tonzpkip.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gt2eekqlyza.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2babvlydw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2kujivutv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2mhjlmgsd.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2doqqtznh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2lfgdejow.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvkyzgq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppdtnhtl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2axrgjxee.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gt2cgoolhht.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2ofdcqbdm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2qmeqbesb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gt2moqwcjmj.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgutmjvs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gt2epedpyiy.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfwrptgv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2mtzwvsbt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bincuvnj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2ecvjvhdp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2yykusjam.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2efsyiukl.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2zcqhchie.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gt2stgginle.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2fsvebgdw.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2widxuhue.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2bvutzgxd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2bwltkpgj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2sxlaomoh.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2bxhqmdmu.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ofzkrygt.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrxwsnmx.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gt2ehdcuzxg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiksoiso.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2pauwlosy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2cjsbkvsj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2quvrlyto.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2wgeggeph.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2hglmzwex.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjfklkor.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsruegoy.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2ietseotp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2qphuatvk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gt2tsrstnnx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2dmrqhdui.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2fxslkcaf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2fklmnclb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gt2dhuwdhol.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbyarfqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2hsutyhwi.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gt2lmiwkcll.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2qoebeerk.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2krxzwsxc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gt2rvxbhcrh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbrsgdin.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2xqvhqrtn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2pvtvpdtm.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2lofwzgpl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2qogxdjnx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gt2ircqxliu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2moxyspjy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2hjijboed.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjzmsrvc.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2hvibfurb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gt2wbbhictt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hwubaflh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2trunxomj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2xbsjetzc.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2rnvlxzqa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ietjuxob.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ngijrliw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2nvstyhmr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2wqsgebmh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgiucptq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2vdphoxxa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2vnrudozk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2ogicylbu.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2eyevhfqa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2rvgqegyp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sxryk.cn/Article/details/gt2okfrwzdu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gt2diagatrm.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2kbftokdq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2ypsfhubp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gt2tvxhhhsb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gt2iqsrmjdc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gt2drepvjcx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wejhiayl.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gt2nncotdol.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2cgivrwlp.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2ztggwopc.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2plwtzghv.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gt2ottryegm.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2konvexrv.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2bnmpawjo.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jduolvak.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2eyrlkooc.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gt2lwjzumye.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2njdlfyfk.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2ysxunqun.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gt2cvsmcivb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gt2cdlginqz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2rkzaozit.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gt2gchjzrmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nuqcrkcz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gt2zpnzhcwn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gt2ysezvpen.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2debyvkpb.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2cxjtgxra.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2etmnldtp.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2kotbbkfq.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2lniobblf.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2epjuumrv.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gt2xamcfkkg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxmbovfk.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqsxwilv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2lttyflmw.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqsexfgj.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2qlzbmelx.html


<!-- 参考信息 -->