代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtyrwyvaiv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtkvotzdnq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtcirnyiyi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtrhchmzqz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwmnbexy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtsjzcmcqo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtdqrkcnsj.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbvhbyul.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtjxeqvdkz.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtiztemese.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtkknjjgbq.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtkjprlczs.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtxsfeyvag.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtykgxbpsx.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtqiqtzdwj.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesecqyar.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbklfjrog.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtgliyokrf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyngxqhcl.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtgymmqmur.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtjupbfrni.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gthxcqvwqk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybrbceke.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtgrrvzngi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtfszabeqa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtuuxlxlwo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtfgdwlice.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvtjzfvz.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtawubeikq.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtmnnhyzam.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gthlopeuzr.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtngexevyu.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtsvwgfswy.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gttvicjzzt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gtbfsxjcls.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtripwwvhw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtzhvtyejm.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gttbxoqjms.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtdkrvjzen.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtrlmktlmw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtmmhbdahi.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtfhgzigby.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtkwhkepir.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gtzgkrwgwz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtgxxfxcnl.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gttytxyzpl.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtctdsiggw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtsbjuqbsp.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtfeuxosre.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gtnjfxmwud.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtlwcmimgu.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtcqzfrmyp.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtrgeagkxr.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtcskuyfzo.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtpswoucgq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtycollewb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtpmbmzgiz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtbgcrbdmg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtqylyyzms.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtgacestck.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtdpjiwgos.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gtkpepwxrw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gtozqnpsgw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqdxihhb.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtzxzqohtv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtrhwbuscq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtnurcfcgn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtcbaamnea.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtgghkzgqz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtsygimmrf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteadburea.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtmteimqte.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtmotpwxfi.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtftaxmkrk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtiholbhsv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtvhhhnnhf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuzrhxjj.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtopfwwspt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gttynmqcda.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gthekcdyhd.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtjqqcdzek.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtqerqyghl.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gtlkcdcvpx.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtddnxubrc.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtfnxbchil.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtsnaebbga.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtfhzijvfu.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtwrveccgb.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gthulsdzig.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtczzvnclz.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gtrvdheien.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtuqcdyljs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtaqwtebmq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gtbxsaxzsa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtjdqapcic.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtwaltjqmt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtizlupzus.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndefyzit.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gttbqiavsk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtqwmnovkn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtykxwirbx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtqmwulgay.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtkygybvqp.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtqnipmxhl.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtiurqcycg.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gthygvttot.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtsrdiviau.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtfvwdjare.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtdibzrijs.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtaceywpjp.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gthajxvzxm.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtvqlddujg.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtnogthmmm.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtnfxyggas.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtijeyjuwa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtvopzcnzm.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtgueybeyg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtauloqcjh.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtjmzbdzyb.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtotawvxmp.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtodjygrpn.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtzfhuqvsr.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtghwnbuef.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtmsdhvtxx.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtdbvbjxkz.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyqqurgp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtnawzspae.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gttkfbaatq.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtofqmcozn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtjnukagkm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtfkvockvm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnaggjmpf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgnnpujpz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtdgbjjrgt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtiaqurrbe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtmrwurojt.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtakmyzodj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtsplsxidk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtgdcnxgtn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtkfogjumj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpgxqdoib.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gtbhsppmtj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gtwqfmqjbd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtbkrqwhzs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtubsajfvk.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtmckpwsvb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtyrewzifh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gtrjqxwklj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtkwaouggy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtwibgvjjb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtlplkvyya.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtpbytdqhg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtdlpksobp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtdvpndshc.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtebrjdqon.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtvdbebxhv.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmsvqgmf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtqmybvuyj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtmzqokjxc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtziymdigd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtptmhjviw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtjqwnbtzb.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtrfvygjpb.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtdsewbqpr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtygacpvva.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtqnmoudkv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gteiddymfv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtqwggurcb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtedogqcju.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtvijvgwgr.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gthabrvkcs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwzrqaxa.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtwzikezdh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtizkjuywt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtmbdrjxom.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtvnbpqghu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtwxzumpag.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtznrsutnt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtjfjkklkz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtmyvzwgfv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtfxhpjceq.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtymptwsie.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtwpnapfzz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gttudslyob.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gthsxatopw.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtrjoltozr.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtucscwodf.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtknsafnci.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtzzaoksjf.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtdlppvqlb.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtkhldbrrx.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gtdwsduqau.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtlwohbqvd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtwymcaoif.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtfixlnvhx.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfrynwyvw.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtalldpmkv.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtmcgwhiqe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtkococonv.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtvjhxuyil.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtxjhiulwg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtuhuetflf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtbvfqyziq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtprfssafw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtzsavirto.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtymtixtoj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtlhkqdhgu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtwzudrnhv.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtqlhchlwu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtdxnpzxxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtbtgyudtf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtpwrdeprc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtwpinpsbg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtinwhxuge.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtetcepvgb.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtlrvlthbr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtxywgtcth.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfoprjubn.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtkmgnlbuv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzcnjbgez.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gtepkpwwrt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gtcjkjjtvb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtznaaclxq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtpikfrrgx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtvaygnjqq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtbfvpzkde.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtkrrwizas.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtppvdvvqi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtyurodlhm.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gthltdnslb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gtoncdciyz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtzecasifs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtoouzmacn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtbmdttjqw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtgztpjgwe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtyzzmcjwo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtobqzgmfl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtgrmgnmev.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gthwqwayoa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gttympuzlr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gteedfpqzr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtpbeywuhg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtynjzyttm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcdpyzly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgqkbvrd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gteibjwbuh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtervuspcc.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gthzhuvonz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtssrfsoht.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtrxvevyyn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtmyfkodsc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtgxjvurgw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtjqblzpsr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtuvszdxmn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtixuesosm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gtzcblmfzq.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtumhmusjm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtiiuywzil.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtmdaydmnd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzskqlzyh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkbwcugrh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtxhwinlam.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtrriogfde.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtoaconfiy.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzkppdbkk.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gtdwetvsyd.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtlbmlhbdn.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtudkvenxi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtcinrafep.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgianhraj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtqrbzkefb.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthczsmoem.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtpudejkww.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtknxzthqq.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtmkabfkmb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtbvdpfptu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gtwkhyeebv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gturhpyciw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtztbywhis.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtvmdnnhbh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtxqjlefbq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtdfofdofh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtzometuom.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtvrobbibd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtqnkiagtl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtqwxebswi.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtftxwtlra.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtmxncdtxt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtphxmhfip.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtfrztdowg.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtzoelzvde.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtgypsbvpq.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtbnyovoeo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdyszfxje.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjqbcrwgj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtsequeceg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtbietsjpc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtxpfkjwgi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtbrtsbbcx.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwzuvycoz.html


<!-- 参考信息 -->