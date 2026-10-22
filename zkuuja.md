代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gt2yptebrbw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gt2fopfpupa.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gt2jdrhkcxx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gt2vmxggagd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gt2uinujhfg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gt2mwinjixn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gt2klqpaybc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2spwnaruv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2habgezgt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpnbkpsi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2aifiezqj.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gt2jmipgydd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gt2iugeilbw.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gt2jgrkkuwo.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2ygfzpadj.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enqiaeiy.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egppbntv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2vpvrtmng.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdchcrbj.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2vcudryhs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzbtmfwr.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2udpahcca.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2nejnktjl.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hivrxair.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2lgayiclm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gt2gwlvaxff.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2engbjtvx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2mcooutau.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2wxeqckcg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gt2iwvdkgie.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gt2efbfjotk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhpaqlqc.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gt2wpvbbjgt.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2dazvpoqq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2omwozpko.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2tzqmznnv.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2pdykrnky.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2qpqsoykx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2uoefcsxn.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2giywsmek.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gt2mddknjhi.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2tnrvdvji.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gt2lhtcezdb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2pystvznc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2xmbbikgd.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2fposkkrq.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2fyfbowiq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2ndvimleq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gt2wagixbro.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gt2bzbnplpu.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gt2kwuewcjl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2pveazhbn.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2obwbapht.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzlrwsaw.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2ljzldeyn.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2oipnrokh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gt2jwwvlimt.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2arrdwfvz.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2pvpgqfca.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkrmpipr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gt2bbzkphoc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gt2izvxhpcz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2eklqzoqh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gt2njqbcthm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2dmjwtros.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2ngienzaa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2atkdfyii.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2dlmcqcdm.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gt2aijwdoap.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2rmfborrt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gt2adjshaze.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2ggjwjsay.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgrbauoz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2dqulmaew.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gt2roxosiyj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2hjiafrjg.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scrzjapa.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2mfxcqzab.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gt2owaacwac.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2onbwlers.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2xhtgmhwr.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdcllugv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vktbslgg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2daqslxag.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gt2uuxxvfyu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gt2ufzqyipj.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2tbltzqir.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mczbcoew.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2ioimyefa.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2fgndqqvc.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2wntlrpfj.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2hntmkbjk.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2sskmfcfy.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2tlkrbted.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gt2htfjkteu.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2hvzvblju.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gt2nbwijaob.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gt2ymuckwms.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2lkmehbih.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2puzinpxp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2kgzjfyun.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gt2bynjqiwy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gt2fraynmte.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iogkyagk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gt2tutbuird.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2tyzuiwtl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gt2aajfjjfv.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2thyllorq.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2abbvthur.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2xievzvah.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwfqqene.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2aysnfxxl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gt2xhspbabh.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2byvhjxxw.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2vitybgqk.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2dxxebaep.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2chyppzvc.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2ysvcnnwq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2mfapljtt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2ftofenfw.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahzocivr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2rinvhnml.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2uhltwgyn.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2ujdaepya.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gt2prkgjtdk.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2htielnov.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2cqybebco.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gt2uqalstbo.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gt2whauiial.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2ggnumumm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktwwrvii.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gt2byzygztz.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gt2rnpaglvt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gt2ujkmkacw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2uryvmmid.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2poznloqp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2veykubgm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gt2ryuaafjr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gt2swxascsn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2yqbpvbqu.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gt2oghjwtpb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afppiiol.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gt2sowpolvb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gt2cpxbpkrt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gt2owrrhenq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2phqfgeqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2moldbokk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2itngigiu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2rlbulvwy.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fiywspug.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ahvbiqso.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2tcbvunpo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2bhjlujys.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gt2zypvrpsr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzhnybsh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqmuzels.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gt2xbmirksl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2pfmyyrwt.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gt2pnrhivwa.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2zeqpxtai.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gt2drhweded.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2florplab.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2wsqrcemy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2wukuurop.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2kdyltlpd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2jiylxwow.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gt2dnudtbhe.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gt2frmmpwwo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gt2lkwolcpo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gt2jjcdsxes.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2lhxowvgr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2kgivaxsw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gt2jhzzbwtp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gt2llfsdyft.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2bxgrcpiw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdukynbl.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2pyqwqcmi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gt2stwnlypv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iujibkth.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2knoswmpz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2gvxrghzd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2xnhachhi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2tyanhusc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gt2wseanroo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2mdwcltbi.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gt2vrorpohh.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2azmkflfe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gt2iyipbjmf.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylppgoaz.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2taweubzd.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2tqpjakhr.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gt2azgavscd.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gt2gizsxies.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlbidcjf.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gt2heimcafs.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gt2bpubgryt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gt2wmhhsobt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gt2jozrrkkb.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2sytreekc.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gt2tvqimznr.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gt2jocxmykm.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2kdzcobcp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hnqiduga.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gt2udyaftpx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gt2ooqgttrz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2hcxdbbfo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2rrtaiinm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkoyvrau.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2zszrmcfx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhhlewnm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2kjlhtsxi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2btkyfcag.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypvwhxxh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gt2vxpnmvll.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2yckzejck.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmahaypv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2aehvjubs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2shjqilmo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gt2uknrpeus.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2uyxptasu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2ikgzxwja.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2asoohqxe.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbjrusma.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ygdrkgjc.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfxdgitp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlujkqrr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2hqqzogvv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gt2jrqprlqb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhjvnguy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2ykacevec.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gt2lkqzjqox.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2eifahpna.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2udakpznb.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gt2ohgqefbs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gt2snhuttra.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2pfkmcadu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixfmnfco.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gdjmohri.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2pccqgsvb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2qwqvighm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gt2klpffned.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzkqnwfb.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxdsgsur.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2arybxpon.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2xirrvuyf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnljkikv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2homrnynk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2vzmmvhlk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2iyerdmzi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gt2nlabpsgo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2ctowqlpe.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gt2brwjktzi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fauhcris.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2vvbbswqu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2sulrzmpy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2cnxajobw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gt2ryswqtza.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2uzkxwwfp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2btnubigg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gt2axxwmouh.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gt2xvvkrgmn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gt2jmyljrbz.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2hoceprnu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2ughddzxc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2uhhutgiy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2nynirdov.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2qexnawup.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2vloyctqn.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2gdthvatx.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gt2znqnejqu.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qqgnizch.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2dgdnqkob.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ooecfnoj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2uicorkjw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2mcwusadj.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2pdmruwgq.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2kuqsfsgk.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2kgpcjtzi.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gt2hksetjwc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2spswysfq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2afqacykq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2mlanlbix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2lusodupc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gt2fzbixkmj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2kbzwzque.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2hzlkogut.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2yoqtlcli.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2sdroduol.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2adrssgpx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2sspsvdpu.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2yiuourve.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2ljtwltsa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjqqqnto.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwgqmtvt.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwwgfwad.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2brxwogyu.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gt2pdetuclz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2jqoxnmjn.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2znuyzsgh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2kbtietow.html


<!-- 参考信息 -->