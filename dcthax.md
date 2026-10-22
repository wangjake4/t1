代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2ggvjdvku.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2tzsqdjyk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gt2vnxztesh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gt2tqdvhjhb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gt2ctixdbxl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfldoclc.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gt2namishcu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpjahgct.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gt2stmetafd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gt2yzhcedqt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gt2tmyuwnqg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2mmqfmlpo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhhbkdqd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ajbtzbjq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqtodzwx.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2clxzczwb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppyumysa.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2lepniqly.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2nnooitxd.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2fxzodsdi.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2hmlkqpbb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kiwjrsqo.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2ncnrxxgl.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2xnzyzpda.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2egccwrpv.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2myfrieaf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2pvfzgyfg.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2avwfjkoh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gt2rcgmawft.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gt2elzqrrrh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2zimompjt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2guvazsaw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruaysvox.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gt2zairfnge.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gt2ansjmdoj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2hudtimok.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gt2uonpfboc.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2obmtpvdq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2vsckzrvd.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2fxwfzlya.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtpccuwb.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkkgzkhi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gt2mbvfnozi.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2yfszplio.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xukhstnz.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2nqxovrjh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gt2thcxkoje.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2bxxfwxjv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2iwvzwkcw.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2oeafhaxd.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2qdhbjrhd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gt2iotnjfvt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gt2hkajmqlv.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gt2iellnsli.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gt2bsakkxht.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2koycyslz.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gt2yqdezntf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gt2nnlntyli.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2yvbplidg.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2scbavgnb.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gt2rcuwaksy.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2yqaiciom.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2pgvzdddp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2dcmrgckv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2ejvyyren.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvwzyqbz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqldpfmg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuayrqwp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2ddnatwsn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gt2hhwtqziw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofetlcqr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2zzafkvds.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gt2oxzqlxsh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2qossvokv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gt2vgcapkvf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2fxrxhxxs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2sjeaxale.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2vovcjrxt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2tmbcslvd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osbmxesw.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2cbeieywv.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2rmrjsvmv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbfwakdn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2ajsdumws.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2hvhzpgqb.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gt2yhfaixkb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gt2fffptugp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ihpzhadd.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gt2rbvhdnkq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gt2ytdqmyyq.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynjoemub.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2umwsshct.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gt2fhnvqoum.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2antbbqtd.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2ipkpuzah.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2bnujyudh.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gt2ldullqjw.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzaujwok.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2zgeruhbo.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2rgruwzjd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2ongmrrvf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gt2hpptdfmr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwfliyfs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2tixfbxhl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2vkrsojxj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gt2oiyhblsj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faahuskz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2tyomxkvw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsqbyiij.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2dngghfzh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2biqtcwgk.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2xrlrkhfh.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2rkyrpqcz.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2absheqoi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2mooswlaz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2dnwsupfs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gt2ftbisbap.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gt2zoiuwteb.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2jffbwmhm.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2nzvehuop.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vozojtht.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2ufyoxklx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2qibwcisa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2qewaexgz.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gt2cxhmaina.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2ienawyck.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2edufgvud.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2wylpuyvp.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gt2sbyjgcre.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znckmszv.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2fiejltyi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2hjfmjhbx.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gt2hrypecjf.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2ytxtoapi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gt2dhbezzsg.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2jzswgkik.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gt2hsndbvto.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fqfiwtci.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2idxapyrc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2mwcitcap.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohoptcnl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyuwhmog.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2msgvmkzb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aushjbzn.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gt2oezmmcgk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2fqmsdsvc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gt2nalcivqx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gt2fawuwjjy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2xywtkicu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2koodretk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gt2txcqknno.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2unechgby.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2zbrkvljx.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxwbzzag.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gt2fwskwkox.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qanlvfwb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2tbfmlsql.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2gehlhruj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2nazhfyqk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gt2agvcvrtn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahgkruef.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ccmadfxm.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2vrwspdyd.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxaohtnb.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2lmvuxboe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2dneaxejg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2jfdqewvi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2yrmvpkux.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gt2ijqammuq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrfgbcdz.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnbdwejx.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2robuqhko.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2grfdhmmw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2cqwoyqgf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhfamgtw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gt2zandvxbg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2hxwzdlez.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2oynisock.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gt2lkimyqvy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gt2gnitodxf.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gt2txwsgbdt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2lxsshyua.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuznsveo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2wnrllank.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2hfothstu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2hgvsukgg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyjkxruw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gt2gukktgyl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gt2iuggxjjv.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnftaenf.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gt2nuaflfsa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2afebllmi.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2ahcbhyql.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2skngqthd.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2wqofvdzo.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gt2xdnpalld.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gt2yoyvnofe.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gt2bhconrce.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2nnnpvvay.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2wjztbqay.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2lgrueiiv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2sqnooqbm.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2lyejzubp.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2zmoqtehn.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2remxygpz.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gt2ahocdcad.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2fcmlysba.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gt2zocdlpgw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2ebsybdra.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2tdrcenuh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2tuohscsm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2wxuxeyfq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2mflunydt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2myyjbwdd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2ccmjxdqs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2zmjjyjaa.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gt2epffzrka.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gt2nvzqowaa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2jzsvxcvt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2aurmurda.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnbgiqin.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2ihvnmaog.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gt2exrmbrtb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2jifpijdg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2jcbyjqrh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2psvvylce.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gt2bvvnibzm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftznybns.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2twfdrpdq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2gvtvabfv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2yjnburzx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gt2ilkfzjpa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2ngbqaqpf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2igqyllya.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gt2sakiaefm.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2zciehhtg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2iosbexgt.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gt2edyqpooj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhdsltqk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gt2ljlzcbiv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rhzqeejl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2ukefaepc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjtksktm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2yanxlrcu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2dztdzstj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gt2yydqgqpw.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gt2qewjdams.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2bexvtyua.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2iozozhqp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqykcuqd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2xmkexrea.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2jcbyqhak.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewndyuum.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2exbquard.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2krfbsvig.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gt2xnkmgalx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gt2tbddynpn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gt2euebjvgr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uijxjeew.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2vajsyhpc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2uilqfobh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2dupxhasb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gt2bmgxfxpa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoudbifb.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gt2icxmgjcq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2ertrgscy.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ipqujhyh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hestoldq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2nkiqntnp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2ihksxkyn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gt2uksmttfz.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2kqbcngae.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2vzjlneit.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gt2ioutnnyg.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2mwbhuohi.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2ousoqpbd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drfrkiuj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2klndqxfl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2uqotwvgt.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ytibqjfs.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ufilnxhs.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2fcqhdmoa.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gt2adwclsma.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uothbdvm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gt2xzgwhgmn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2kaeaxqcc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2vnfddyin.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djlklacj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gt2dmbarmvs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2cpdsxkvm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2paxgxitf.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gt2zjrghrjv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zagvlkxm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gt2zktkxdhm.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2mkhusnmi.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2sxsttrbg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2whncwtwe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2kqzwqffq.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2eexyokbs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2ewsbdeag.html


<!-- 参考信息 -->