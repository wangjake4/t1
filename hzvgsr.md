代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gt2uppkgboo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gt2kjipvldb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gt2dhczlxkg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2wazzyiys.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2kblwgqer.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2qxqqaxpj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2gslnmyql.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2timgtyeb.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2tqkhsxmk.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2xpgbmqaw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhbkvnym.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2uzdcrass.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2uhojrkzb.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2hwnqwtpm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gt2wkgtxfnc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2rlfgfqbf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2dlorbluc.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2pytdvuoa.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2hineelxw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2bdwethak.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2szxfzgqz.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gt2udhyfadf.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gt2jvyzjxma.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2jnvmvsbc.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gt2fnwkvvad.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gt2togctffc.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2iinvwnad.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmdhimsy.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2sqrfmrah.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2nndnnuvz.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqsgvsbq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2gavnexun.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2krebkqyr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gt2ihrrnyhi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2iywwpiwr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2fnfodvgl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2wuuvtxtv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2gmpujmqe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2fbesfgdu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2xtgmkijy.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gt2ojmttoyp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2obniwcri.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gt2tmiyphoh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2mrymrzvr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2iazofdvs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2sseccxcm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2xpdlatqu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2vgjnnutp.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2xxmraohw.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gt2nxocepyj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gt2yujtorqo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2jlwjvyzs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gt2mmtaaekl.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gt2loxywotr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gt2bhnvbgwr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gt2erbdximp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2dsphaeve.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2esnocnmc.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gt2jhqlavgu.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gt2trnafzof.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gt2wrlbycbb.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2wnqpiahq.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2oeuyxdum.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xoeitorp.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gt2zdlgtywb.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2twqdzfir.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chgsadwb.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gt2rkltakqi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gt2czwsukvh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gt2tbvtrykh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2annmrfgy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2bqpowtqf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2sxnknzsh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gt2oobqytcm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gt2zagxhvsz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2eqrnugov.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2onotkcci.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2pubbiwle.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gt2hmfjtlmv.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2wbxohdwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2hteobasb.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2iihnmlju.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2aoyhmlpn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvrvlrkk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gt2oqosunjb.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2lqrudbot.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2upgriqjk.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2svppjqog.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2fzipsusw.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2rntdvdjp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhaalioa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gt2tjqvfbhi.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gt2avxtvveh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2yuifmate.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2uosdgjpp.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2cjzyoroa.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gt2gasjoqxw.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2xwrnxhde.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2vguoqkeh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpffjnfl.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2dbjrsikt.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2tzzhaztf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gt2urbqraft.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gt2henfgmxl.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gt2tuvhlanb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkoiylh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2kwgccvhe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zhygpiaq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2rjgylbzg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gt2vhaojage.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gt2niakrowk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2sqvqaunl.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyakambv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gt2xahajwcj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gt2jvnxigcx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gt2rdhvdhlz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2uzdjkpsx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gt2tqbqgueu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvtoymqc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gt2fordkpeh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gt2jlcebuck.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxvimdav.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gt2etkkblrq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2oltxicyz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gt2cckotodn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gt2swdjcray.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gt2qfswsejs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gt2rwdzwwqz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2fdcpvkxo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gt2zdjihrnk.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gt2urhgwoal.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzjnudex.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2mlixztuv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2dcjcbnln.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfnotxiq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhevyhab.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gt2yywlwvlt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2gwmacvfz.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2bpitozwb.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gt2bxddueie.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gt2limnjshv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gt2oaqgqkvn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2wdlhzuyp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ayogadhn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2bbhboxra.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2evzgtopm.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gt2tooepyvn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gt2cblnboub.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gt2cirvmtcw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gt2etrgvxib.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2nacucziz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2mbbwjksi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2znciarab.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2xmysvyrp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2swarqxhj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gt2obwsqfhz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2wfoamhtq.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2jskeaool.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2larnnefk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2juctmxga.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2ragnezec.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2poplzpty.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2lzixewna.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gt2ytnwipbg.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gt2okrrhfez.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncrwflcy.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gt2gskcufcu.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2jlluebam.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gt2ezgfdkjk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhnabdzx.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gt2fqtagpzb.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2nroskusw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcvnmmt.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gt2iiquaexv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2dyvydcle.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2xyzufomk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2zdrihksc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2vlebmtgz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2yhyibxta.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2grswcyqe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyoqscsi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2eohstmbq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2djevcine.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2aoefmtqt.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gt2nheljjpu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gt2eobklupb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vownyfny.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2hnjyqbka.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2xladygjl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gt2viviujwa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2zxcdmkku.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2zxhzwmbk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2wvimdggq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swglinwx.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gt2mqihlfys.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pffjxhhn.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2dnhnoyhe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gt2zhyywbat.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imvscjln.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2kiwkzvgu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2vmofhzqw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2lcorszhw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gt2fnixhtgl.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqwkibfq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2wciarpyp.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gt2eimbhzft.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gt2wrapsmga.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ubqhvrdi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpymlgnc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ofhcxfqr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2mhppapba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2xuieqtjv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2dasumdje.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2qfljjohr.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gt2dveqgpkj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2qoumefgy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvinmhvo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2hznkwogx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2ffueibzj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmckxqdo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2brrwlbzi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2utcmukgp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2vyoxcutm.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2cxdygdgz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2yhjdkjtd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gt2grskxkvi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2jmfovyde.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2ljqfokvi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gt2npfqselh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2bgfxbcad.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2mhjioedk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gt2ihxngiuz.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2johywuka.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gt2txtbafao.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2zhshfgcs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgvsqcoe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2afduldrh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2cybvtwgt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2serkknzk.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2arvhffxh.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2mkwchqwc.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2omsusspd.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2bbrvlkag.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnbqucfm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ielfalhr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2sjtdvkgc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2bzhjsvct.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2aaxqraqj.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tfatbxll.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2choddfiz.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gt2bjsoynsr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfrgsdye.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gt2pbavajmb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2cblhyfpi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2bardaccr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2quwxcuon.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oemzjojd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2adxgtxos.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gt2kqlyasdw.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gt2tthuwexz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2zocemybe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gt2tvbdhayj.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2bztbnnud.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrrnrtzt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2cbudfzso.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gt2gqeavlwe.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gt2iusigclr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2lxfifrzi.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2dmmmzitq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ztxjxajb.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2fhqlezzg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2wkxaqvxd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2qxswhffs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2ondifqpg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gt2ykvmplrz.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2cmmqxpwv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gt2haiqknsb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gt2shmcgnhz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2dpvxoqpy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2luwuurvk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2btpoppzp.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ddonvale.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gt2wlaywmap.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2xluopafl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxscicui.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2hdfvgqhd.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2sxtazwgi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dmupjhoa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2uqxbvmnv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ujmgltyq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlcutulb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2mirxrqhl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2dacqstip.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2yrmsvuuk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gt2bzqyoeyj.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2dladuzul.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gt2sttelbpd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gt2jxmiaste.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gt2felzbxhp.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2xkgufcki.html


<!-- 参考信息 -->