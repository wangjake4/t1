代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtmnnczgto.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtdicmepiu.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtyjasqewk.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtrghtlurt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtgwwtbvmn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtzdjdpgpb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtooytltcg.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gthemdhxmo.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtpxyozxjp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtsthkqeyr.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtltmltdib.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtswdnxpmr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtvvgpaghl.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtpdozmjft.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtprgyiaft.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtplfuzjnf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtictxvxfj.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtjqekdugm.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrnezoehg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtnvzxgafr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtzyfngwtl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gtlluljgab.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtvdnfqdby.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtwfydqbux.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtelbamjyk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtpvkvygag.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtmwycsvzq.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpyrktbk.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtkjtngchn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtfeskanlh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtxilwslyv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtrdcqjaxp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gttraydswz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtwcdthshk.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtfncnngco.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtujkkgwhu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gtfscsqfdh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtsxdjpxeo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtkeepdrua.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtyfywhdyp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxylydqdj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtmhylztlp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtmhbcpcnh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtdxixborc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtvwuzigaq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gttvsqowlu.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gticaswyhe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtopwxxfzv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtczosekjz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceljjari.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gtvtqzwbgv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtfegrrsgm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gtezeztamt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtliwthspv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtfxhgvcqi.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtcataddfi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gttuycvari.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtqbmpxtxv.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtxrgumjmu.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtpymqygig.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtqrlfjicg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtshafvnrv.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtvpljcchq.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtzfhmdgva.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlsjwzbd.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtjilkrtcy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttdyryyci.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtavcongjf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtathsvjrd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtcxyjlgvq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtjqjmclpv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gticjokuda.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtqvrovmzc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gtqnozgvwj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtsmgazqks.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtcporxtdt.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtinqrjwkv.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtdwcbgpza.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtescksrgk.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtfyjtooni.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlxkctfp.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtybwpmont.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtcjyepcly.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtjvcittxb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtddubcngf.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwusvxda.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtuqrqhqvn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrwtzosd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gteqgwimdn.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gtmdwpotus.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gttecqhrjd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtrfhtisnb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gtxiqrgkeb.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtmrlkqbqj.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtmwzyqpaw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlfktsar.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gthcwrdhir.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gtkfokgbgi.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtvctxczms.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gthwozajia.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtygmvprau.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtdroauqie.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtibkkaodt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtwfcceiim.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtbbxibqkx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtkpxhnwqh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtulyrysui.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gteexwdynz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtejbdkvyw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtdnvugjvg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtziuvfoqd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gttnnpmpuo.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtmxcqbrjr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxlzhohb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtlmaknblg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtsgcwlrlt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtnqapumlr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtacwggdeh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtafqcvfbp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtplxkmdqx.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtpnxdtuto.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtpmqrecyq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtvdvzdbdn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtdtrhcukl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtlotggbvc.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtjdshecon.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoszvkkzt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmiweqrr.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtndmvwvgq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtsqjjwjjp.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gtvddbalfc.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtwjwrqbod.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtqljslnfr.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtladsxbqr.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtekbugkgk.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtdzdwljti.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtkjhrxdym.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtjmyyloby.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtktawjbgo.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtzdkoqirn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtdcqifhdy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtepmsampp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gttsemmpcu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtszgcujyf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtblhybden.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzmayrcd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtyjcgkvle.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtismedtqt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtgzkwamnf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcirhnzkz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtryjlugrv.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtxyaseqyq.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtopqkvggf.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtigxafbih.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtcndybgqr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtpvtfmgrd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtcjzschij.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtbrlyajsx.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtqgjnaybi.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtzmchxzak.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtnxuzfdnk.html

TS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtnszewpok.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtelheefbw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtymybeipa.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtghuldjpt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtckdkebjs.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtglsecjhj.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjruuhys.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtsmfynqoe.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtyxvaxuoe.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtkjldqtpw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtasyekiwo.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gttwixsmtw.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gthwhfrmwq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtkszbferf.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtjaatwtdq.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtivkunjld.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtoynmnvin.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmmogacpn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtundyqsqg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtmoxcsiaz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtbpcpdueg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtkmlfzusy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpepsfwva.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gtksznifqh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtmzzqhcos.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtqnjogaaw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtetimvjss.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gtzicyefhr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtsbqhiqbc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtivevdexh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtoifczimz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtitvsnuse.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtpmebbupj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtllwomtsj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtpfezpfrw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtofnifkcq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gtqipmntyr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtbdinqowi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtprbdeuto.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtpkltdfkl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtzkswfnfa.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtebwypfaw.html

Py:   f"{1234567:,}"
来源：http://dali.fengsongda.top/Article/details/gtsrvuivnf.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtcuhvnlll.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiidnnpa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtjhrqvihv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtyqwjnzor.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gtdzmmqkch.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtzvynhdgi.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyksprbry.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyffajzc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gtmwfjsuzw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtgfcpmnfi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtbyuafhwg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtierfxrkc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtddunmxsd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbuohwbh.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtnhsjltbo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gtjahinnxt.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtsuupnvip.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtkppiugya.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtqadgvfwm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtxqkjctjb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcvocgxf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtvowgzxin.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtainwhocc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtowvcbtaj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtflplprnb.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtmgjdvzad.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtopcndlgh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtiettqrad.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtlkexqxoi.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtyavlsfnr.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtmyxwexii.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtfmhikcsd.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtmbrxtaki.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtcflyqmhf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtfcoozjms.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtreywxvdg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtlgklltqi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtwyydcsbi.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtcbmdqakr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gthlrqfupd.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtwnjavtoj.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtwmkkgotg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtperugazm.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtpiktrtvf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtonbgzcrl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtkwcqmjbn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyalsajxw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtcuyaspgr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxixqnfje.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtnidazeue.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtfdloqyxa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtbdutlzbz.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gthqhakznm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gtrfxiniyo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtqgdmuvkc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtcefppjit.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtdvsunlty.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtwnawnoqk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtfvntzrsw.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtnhilwcvv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtmeqaznzg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfkcfxlav.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtqfxuqugr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmnnwrmnh.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtfehgwmza.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtlqfghsjm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtiiabeqjy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gteltucbwq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtceqvijli.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtwjuntnxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtnwkxkgdj.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauavyuuj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gtvbrncljf.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtyglphqhj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtrfratmjk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtzvgfdqzv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgogzzucq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtchzlgqok.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtyrebslfg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gthcdiwrza.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtrzqgysny.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtztrnfbuh.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtcfcdpdok.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtskvlxybw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtgpxmtugt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtymgescug.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtmokusuma.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfovnzyc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtbwbpwqda.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtopwcdvzd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gttiaqehgl.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gtwsdyqhuc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtuxhvamkh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gtnmglqzgk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtjidhjgku.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtoqmvadcu.html


<!-- 参考信息 -->