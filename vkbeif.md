代发 wailian999

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2hhlxgqxe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gt2eitcajpe.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2bnkpofew.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2dmsyavpy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2akmgrfvm.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gt2yzbmrbwa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ynxcqpjc.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2hgqgipdz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gt2eqgdelwd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gt2jmgvilbp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzniyxbo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gt2qkwruhfd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gt2uuxjjejj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2txqiqamg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gt2dnjhbyts.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2zrxijbkr.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxraantf.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2ieiopvhg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2npgmgfsf.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2imbkixbv.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2jupdfuxs.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2bcnnrpic.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gt2yeujktzd.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gt2xcuiyalm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gt2lyguvegd.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2ktklkvdk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gt2fjkbiexf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2zvcxnthb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2hvsasluv.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2jsoabtei.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2jkevgbnz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gt2rjreqyle.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2vtfmedhk.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2dugncmsu.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gt2fghpmdft.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2vaymhfvl.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gt2keicgblh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gt2cmpigbnn.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2opmvckgl.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2sdffxeno.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2srebcwhd.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2nwzquemy.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2ezxanxdi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gt2euoynrdl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gt2pxunpqzk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gt2leptmqfz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2htwoaifg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2xrajwqvm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2oqszstei.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogsakacr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gt2tatwofem.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2xhyjomnf.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2yslyohou.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gt2wmrodhxd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gt2bbjkcfhg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2jelumodb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2cbxkfrhb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2euznxzcm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2dgjlfpmh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2ubtztgfu.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gt2uhzpbbte.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gt2pmtshomh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gt2hugxemiq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2drcafahc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2mpmyboqs.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2fonpewqi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gt2nohmgbpf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gt2endxggdh.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gt2bicdapee.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2msoihduu.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gt2yntamxjz.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gt2xjmlpxmi.html

PHP:  implode(",", $items);
来源：http://dali.tianlin.xyz/Article/details/gt2pyxrvrrj.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2hvocbilm.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2crazasds.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2esufotjs.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gt2ummhjezd.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2rpteurbk.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmgmtwtv.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2wdzrxaaw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gt2qhrkjmkb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2rxjxrlxf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2cvmqlyhf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xopeqdjg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2hoxutlor.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gt2ahqnvqrz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gt2bbtltbxi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gt2yhtbwvtm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gt2njldodcc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2trvcdqdn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gt2wknvxxgk.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2knqvruyv.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2bqcmvpby.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2fjipgtqd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2jowmwhpj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2kwkccfta.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2nuusiawj.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2vhbeigbz.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gt2fmkvsgtt.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2bptfkjqc.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2hdzsgtwp.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2vzthxoto.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2fwzfvpkp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2ikyablmp.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gt2gcegwueq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2cmlmqfhu.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gt2ojfailcs.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2pcscyndz.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gt2uuqphrgm.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2zjmcfywa.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2uumyaczh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2guymqctm.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gt2llwjatqu.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2xrlkxlja.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gt2elkzcoof.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2fztzldqm.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gt2agjkupvc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gt2mbaanxsg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2rhhrjyvp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2fbfjtier.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2oxdwpfrg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gt2uhumepdu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gt2etnonxrt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2foqydbfp.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2jxetctdl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gt2mxmsmneo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2pybnmigl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2yeakwutc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2acrexqpx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2mxfgmhic.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gt2qqqgffmk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gt2qmdjsjub.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2sgvihsno.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gt2qhjqjwpp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gt2qdcpnpbv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2vgixelii.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2yucqgojq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2plxxwvea.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjprnuyn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2segnzius.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2uzsqumhv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2cbxkwrsw.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gt2utkypaqx.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2yxuwcstf.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gt2uedngyab.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2qzdpdjqj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2jbgxwcha.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2grfmgnzt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gt2utgvazim.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofipekqg.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gt2lcivrjma.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gt2rwpbukvp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gt2gyshgris.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2wmusoiaf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qftxstbd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2eyuagiia.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gt2gorlsyuo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2hedmixed.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2poarcmlw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2ycasxhfs.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrtukgxp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlqkouly.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2ykdhxxes.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2xawavebv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2kuwvhlcv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2ekpcennb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2nfduulru.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2wxdbxxol.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpivezbw.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2actyhnse.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gt2ldljqfdy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqkveeak.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiadyzox.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2qhyypkqa.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2slyqhofr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gt2qzymzjsm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nwujxvpr.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gt2klnjaodq.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gt2whbsrobw.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2xgvbengl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gt2pwibknpo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2txjvurtr.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gt2touocclb.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2afcizvkf.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gt2icjendav.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gt2tefrdksv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lucdwlmq.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gt2vrvibjge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gt2cmiwnjrs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2itukyoxw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2matxjzri.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2osublehn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2ajalojzq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gt2jytvadrp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2eufhftef.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2tcpbnfco.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2huxrvsdb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2nmttdnze.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2iaoddflx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2wlfrtlej.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awmlttmn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rycyhacm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gt2npvpotdk.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2efkrlszg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2iicqjafv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lewhlxje.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlgitepk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bnfonbxg.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2oyehqxng.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gt2khwxlcud.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2foynqoye.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gt2gqahcndx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2shigacji.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2mhmazarr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gt2fppnicnj.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ujcubmjv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2oqlokjsj.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2nshxeqks.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2wuhexwpu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2auflbrjl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2qydlsmem.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2xyvavugc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2avphmvvt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2kdpcyyif.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gt2azaluzog.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gt2dlsujhjt.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gt2dmmrzohc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gt2uvifhfdc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpmslwku.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2djxailht.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2okphinlt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2rxflzfso.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gt2bzxlaoqd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbltgxrv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2xxasmdrr.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gt2erpdcuec.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2rwohwvva.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gt2xuganlab.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2apfwclcd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2dkpvwplr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gt2dpjwcolu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2vfmcnoug.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gt2tlyesuwh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gt2wtirfrod.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gt2xolhjyot.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2amsguxuw.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2yrsybeeh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2yfvezelu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2unjxejcn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2iecmsiix.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2emilgugs.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qezxftvc.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2icdnwzhn.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gt2uzftmeas.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2yzjeaqtc.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2scosmsyy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqxzkzvi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2reisnxva.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2ajtieglc.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2tqnowiks.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2dsasywtl.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpdfcrqh.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfdpqyjg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2divibvxw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gt2vfqftfbq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2padlxidr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2sjozotrq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gt2qaztawbl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gt2ftasfrvw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gt2bqkexgjp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2picobesp.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2itlstbhn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2dvvodhye.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2flohztxt.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2skuqtgye.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2froimwfr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2hbcincar.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2zzpapgkv.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2eiqnmjwt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2nhgioqqp.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gt2xhzffqee.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2sxpgtvwe.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2ivcyrpff.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyiabxtx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2ctlnpbhr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2fnpyxxfc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2ybxykpwn.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2odjuvibc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gt2otwdksdg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gt2afnzaema.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2vlxdxiel.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2gotjosbt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2qspnvikc.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2oeokwadm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gt2zdvlytro.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2dxryxgom.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbcwpnqu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2douggdxf.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gt2hazftrjs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vieidwju.html


<!-- 参考信息 -->