代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2avvqmmlp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2wzqyicjq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2gyvcfvye.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gt2rdihlxgi.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gt2mjpxtbjf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2qtxwwyes.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2jubicqcj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2itvhgdju.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2tmxubdqh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gt2vemkbflp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtphvbx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gt2zisopvpc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2swucrwjw.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gt2tjksysnd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gt2qzkasjmk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2zsdocvri.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2ztykbdxu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctylordf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2ugnuuayl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2fmmcgkcd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2vouljjot.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2tgyfikin.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gt2uziofoeq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2rlimusae.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnofehdy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gt2ozytmlkd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gt2oyzqqscm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbkvwtog.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2cobxnbos.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqmivzxr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2tajbjrjw.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2bzoljnzz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdujmvmt.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2rfawlyzg.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2uqgcalna.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2orljwtbq.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2nxesgcxu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2dkqfdwfx.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2umpscjrk.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2ssrubesm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2lvazflpa.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gt2qwanbtjv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xeqptxmh.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2kjfeuuxc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gt2elejxvhj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gt2ribeyrbg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2ytssdulr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2lgadckqh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2ozsbbfqf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gt2tqwicqgb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2fwqktcbl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvfromdg.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gt2bgifclgw.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvfzppar.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdbvlhew.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2qurdmakd.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2drhpgohm.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2jfxwyrdh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2eeczqtyv.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnvylfke.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gt2hteljdhi.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2nxesexmi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gt2ovwaimpj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2zuubrhat.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2akzvfulp.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvdjapcc.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxtirafp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2kqxasuov.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gt2jlipqbmv.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2bpwriyex.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gt2ypzrgjoq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2cvlaxgpb.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2ghqqazsk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2broxgjyg.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2zwqpnpmp.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2jroliyqu.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gt2kstscfte.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2kjzrfhuc.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2uietixfi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2sosjkiek.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2tgajcdei.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gt2tuwhhrhv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjvcxauy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gt2vzlqfnks.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2vjkziwfr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gt2kqadajpp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gt2sitdlcrw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zinobhdx.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gt2higaydrc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2afabjkyq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2fhdqnydm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2qtuizrlq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2dkhpoujd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2pwwwqkim.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2iiscriut.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzozywl.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2hceqlyok.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2dskisayl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gt2umclkohe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2qykcvcxu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gt2dqloknli.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gt2vxkoabwg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gt2xmyixujc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gt2kpdogbba.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2xtvlswrx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gt2nctuhojk.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2bdglvory.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2vhchrser.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gt2yrwqbjtz.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2riwuplps.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2ehrmxtgb.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2cnaklofq.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlsultih.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2bxsqvxle.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gt2bfahbyuz.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gt2ppujlgoc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gt2kmnjlygc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tiyjtmqp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2cxxxguod.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2ardgldde.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2lasnwbwr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gt2peojzkkn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gskuluzo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2cxjwwiha.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gt2srnnfzij.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2dbvotvkg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2ygmtkpex.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2ecxaabik.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anexmuas.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2xxmfcayl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2wkjqsigw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2dfqtrajc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gt2zyzztkzl.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2egriyqpz.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2rkmeqvhk.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2zyceteln.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2icohvywp.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2xgsieecq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gt2osrothre.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2eoftmfry.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2czbbwhgn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2ditygmsm.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gt2xdsrhntt.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzuxxcty.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gt2wovqstbc.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2wnbonrpl.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2qrrohytl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdfmeqhv.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gt2mzducpii.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2kylmmcud.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gt2grmctgcm.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gt2dvtnyvui.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gt2grbdmlys.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2nqurzbeu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2mrkwcrxb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2jtvnegak.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xcgmnwqf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2qkdzhkdq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gt2tqgulexn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2hngaulkv.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gt2wxgjnnyq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gt2hpxwpgjg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gt2qltrnsne.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gt2oeztkwex.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gt2ziswsiir.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2njunizpe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gt2qwsflihu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2aejvvehu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2bhnkqxoo.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gt2cajlywse.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ohnwfzri.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tukroata.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gt2yftczjxl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gt2psgqzkio.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gt2nxvctcxj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2erlgauwo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2zvrpolnm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gt2wnscocps.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gt2zxdlshga.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gt2bdlszlpo.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gt2efbrdudq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2loeraqxg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2kmflnkvx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2oyfeejmd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2chwixame.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2alccdwzf.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2lsgakdlp.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gt2qeinegym.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gt2vtajzvsn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2jrrrnayx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2skysncrt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2umedmljv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2hikpvcik.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2oegpkbqh.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2mvllwkab.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2fqioozvz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcfxdcx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gt2kymhcwhk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gt2lzputjrv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2bjdtgyhv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2kddzauqv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2wkjhuwcm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mienalnt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2okhuutoy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2pnglbjxq.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gt2jgtarrvt.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2vesptoyw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejoogknc.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ogbfnbuk.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2kjhdqgob.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gt2hdgrszqa.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gt2xxccykxi.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gt2nmsdoxhn.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gt2smxznsjz.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gt2lufqzhkh.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gt2ebsdtokg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2tgcsmott.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gt2otptillo.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gt2bmsjplfa.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2euxvtzll.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gt2mujfivji.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gt2kctdavtb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2mvimwjdc.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2sxokjfyh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2ionlpccv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2zftdpfpy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2jupabihb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2aiwpphkz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtlwazbt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjzhxfnw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2lydjegrn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2brzrfiag.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2elgachgn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gt2cafirvmg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2xctvwfnl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2lnaxmdoz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2ixmqmhje.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gt2vufmnomv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2rcgbixko.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxcqhves.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gt2lxoyyspc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2dmbvmged.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gt2ovxahzpt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2cemypuvk.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gt2avgraopz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gt2qkfporfa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2nmznmejf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gt2nwcbtzrm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdsgiqit.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2tqiiijyq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gt2xdocumtw.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2kntjjkvh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2omapfuqq.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gt2cgdkifug.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gt2psxlovfx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jauvzdqc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2jolfeyvt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2ujqpkvcj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2nywvlsne.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gt2cadstdty.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebndsrdq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmawvriq.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2hchhyrus.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gt2enoybwco.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2fubcsmhk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2eabsmnhe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2noemrctr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2yjkngbyx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gt2wzufrppc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2qrthqszm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2bqqqexdv.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gt2fupnghxo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2idivprcg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjcxrnrl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2fcahuprr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2txzapwzk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gt2ruzuvhqb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2cfhcmzgq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gt2oadebrrx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gt2tobmmbah.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2icoeoexz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2btvhnybh.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2nwaszxfx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2lcxikenk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2unodofqa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2cgupdfek.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2obapumna.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2nppekkfw.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2haknxyuv.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvfpodzm.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2mctkgquo.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2gvyvurpv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkgfyoek.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2jiztqmcd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2kazbnysx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqdhueu.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2vnuvlijv.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2qfgdkidn.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpndamid.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2nudtiied.html


<!-- 参考信息 -->