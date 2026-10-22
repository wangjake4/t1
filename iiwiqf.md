代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gt2ibsaaqtb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gt2eyumghxh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2dfhockdv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzhxwjar.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gt2xyasiqdg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqrhiows.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gt2ehajytzd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajzlrgcx.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gt2tnrwnguo.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2kgbykxgy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gt2woxcwans.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2clsytgpb.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2jlprsuzz.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2pupcnetl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2wqkstcbe.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2hkofvggq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gt2fywjbjje.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2bbfcogzp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnzuvaje.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2rthhfoox.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2mszfykon.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2zmxmktcp.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2lsypgtbj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gt2dentqkon.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gt2ndyrctao.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gt2ahwexwia.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2togbacsr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2htyxeaxt.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2kvmcfymr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gt2hvqidaid.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2juwsdfgj.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2sxnebjka.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2zwzlpwod.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gt2vvwkeuvy.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxzxesmd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gt2imknfqtq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgwwokbc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gt2reqteguk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2ckophlhx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2rqkuhjpp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2mhtxltyg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2ewgpbvaq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gt2sbjntiis.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2jxcgyccz.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gt2bpcefawj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2udffrwnu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gt2tamgaxic.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2xnjkhezf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2mlxcsiww.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2jwdypgdf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2cmcwjzrm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2ufyfiasc.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2xgyukaic.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahsoigvr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gt2rvbvmcva.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2zggdtpyv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gt2mvzzikmr.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gt2hhtkisnd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gt2fbnroknr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gt2aupvyfsp.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvmnbyig.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gt2doyohyys.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gt2gfrhwxkh.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gt2ivhwkmww.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gt2rctscohw.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2weqlfdpj.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2tpgdmevr.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2eywgootu.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gt2otnalgxz.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2dszbbjnz.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2htvlgobo.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2fsmkrpei.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gt2ziadiqfz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2pqslmkcx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2qwevdkku.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2xuyyhlfr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2dfijgyaj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gt2iuwgojou.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gt2kjaufncd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2nirsqssx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gt2dulnqowa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2ydxvwzwb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gt2gjrmdvkt.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2hmvegmjl.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2ndmdjbeu.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuazhtfd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2mtmjsxzy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocmwbgcx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtrndlbd.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyyorvfd.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2tvgoylpe.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2cimsoffw.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2rjgvyolo.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2fpbuazva.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2wgjwqbjb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2xpzsaqwg.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2ulimtqaj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2jsqedmxg.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2pxaxdwfu.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kenophwq.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gt2eyltblfk.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2xjfptfxh.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2qfwpvxtq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gt2iwoiitlx.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzczhdak.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2gojqxjuw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gt2iseilbzn.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcylbxbv.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gt2jtymtmox.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gt2oicmkznz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2lrmqlcvh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2quhxjfxh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2beptuoxv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2odxxmzfc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qaoptgcd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2cdoaevjy.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gt2hwbfydek.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gt2hmcepjez.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gt2nwjugnbr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2bsbipwmm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gt2nqmuglpq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2jfbawlsf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2psrizaqn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gt2emegqooo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qonhvinh.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gt2vqmlpvdz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gt2wooishzs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2ducypqvz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2daeiagqo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gt2emutllxx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gt2elulfktw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2bsqtsgql.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gt2uecvkqkb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gt2daaznynz.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2azhbyqrr.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gt2pfrvcjjv.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gt2ogsljxzi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2qbdtkjko.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2wnulvame.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2sywadhnc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gt2wnhwgmjz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gt2xlqhjxiz.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gt2vlzfpvbm.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gt2xgbmplur.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuakoxo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gt2pxfcxljy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptfyjbbk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2jgnhuano.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbiyirsy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sylospqc.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gt2ttoipdkj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gt2hdvewvmm.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2eokvtfhg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gt2nbzynyur.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gt2smylyxne.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2ikiwtnkn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2lrxefblt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2jhfkbvor.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzvysqng.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2xnfaxykp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbnhtnbi.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gt2hbrwesoz.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gt2qyrilbea.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2fixkjidr.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2rtxypdjc.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spzyguio.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gt2pcmypwag.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gt2bjftjsbk.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2qtltrhyu.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gt2ajvnadwv.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gt2bymnowky.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gt2ncepumqm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gt2ojefqwpt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2wklddphn.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2subiiozf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2zzbutpbp.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlwlqfx.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2ecmwdfuq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2klegklpc.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2ptcgllnw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gt2qrjdeujz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2otnxytdn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2sahqucwj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2gzzmlspn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2tusnknrk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gt2egdejgyk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2bzousjbr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2xovjqgem.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2oyjnneec.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gt2jkpvzpzv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2msukehqn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2kafilafb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2vwrmmzei.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2kxrjmmwf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2nejhadqt.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2tediccxm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gt2rsswofoc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2mpbrlhxp.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsrjjppz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lxunhlft.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aaegfdou.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2clqtvjdz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2jhjhcprj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sayfbkfg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2dalhwuvw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2pobbowtr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gt2bchiyhkk.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2yxzsbjbm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2fokogvyk.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gt2zmjzqawf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gt2wfszlvvn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmtgxijl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gt2kydutqhr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2hmjmwstj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzrohffk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gt2chbpkooq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gt2nmnbnowg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2vkztwzne.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2wcqohvul.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2lrlmxrbi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2kkztfsqh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2pnszktde.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2drnstskb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2ndtlrvjo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2zirwsbbu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tukotgwk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2enkemjvl.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gt2wuntiqln.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2vqhqavny.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uonmzlaw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2gtmprcsm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2dutbcrjy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gt2jomovian.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2iwagykni.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gt2ltkywixw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gt2kkyvxmpr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnrylwrs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2dhdsqhjp.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evghgnna.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2zehadolj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2anbqyodt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2nclzbxww.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gt2fmxubdnm.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2lisoloed.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2pxtzdrge.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gt2nrkdcqgy.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2wopzyofq.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2jxbroaac.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2asfsroha.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2biznrurm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2hnkevdtj.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2suibmuxl.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2oontcrzy.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwwyuckn.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2oatypcbs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2xavgnknw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gt2juzjoyzw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2whuxcwgs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2jpvblufv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gt2vqnverrq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2hejydqkc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2wtkxkoiw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gt2mtxupeme.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gt2sdoewloo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2outyqlqq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gt2xbondfol.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2ggfdjqeh.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2hyrjdlle.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2rwtjagla.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2trambbra.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gt2xtfryspv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gt2dxcscqyg.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gt2rquoqjtp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2kanddyxo.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmdkxvnj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2anhgslsr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2gsmmewdq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2pxpbzhnh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csxwrbke.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2oysrxbyj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2ifxfpfdr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2wwyfgjcw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2yjumwrli.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owmnenpg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2eatwqmph.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2niftfubc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilpwytmw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2efmqiaua.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2uhuqqtto.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2yvfufmix.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gt2snddjgom.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cbqkifxr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2nwtswbyf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2nutqfysf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2qwtnzynl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tduehaex.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gt2wljytldf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2vuehnvwv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2hkomwkxr.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gt2vopibtcf.html


<!-- 参考信息 -->