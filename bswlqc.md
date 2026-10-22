代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2axgmtibk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2dshpzbyw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gt2soxodzre.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gt2vojmxwtl.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gt2qscgposh.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gt2mejadyaq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2nzoxsiug.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2hqzvikgo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2srhrgdcw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2kqrnyyng.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2cwxwdnhp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpfvghp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gt2jarfvhhw.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gt2fmdiehal.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gt2qdqszley.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2ttvxcbfa.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gt2bnddslub.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gt2ceoyjjrq.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gt2tmgwrfxi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gt2swsxsxpq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2hvmhqaqy.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gt2rmssxdyg.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gt2sairkyka.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2jnhhdrxm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2tweqmutj.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2flyigbpg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gt2jhuonumq.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gt2esfwauoz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2vgbvudcg.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gt2ryyhjdjj.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gt2xrrnoqjz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2slvevblx.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myejlfuf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gt2ocauglut.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gt2bsvaalxl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2bnvfvncb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2gebhfuch.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gt2aifeciqi.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxdskggx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgpnanfv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2marjnspp.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2pvxxukvb.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ydzeivyl.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gt2apxxsgnw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2mnroizyx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2acslafye.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gt2vbsphxdl.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2rlmqvfjn.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gt2uyhnqfhx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gt2lmiihcnr.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwrenwur.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2sfmauqur.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gt2nnaffxsz.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2yrrdfqih.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2yqvvuzpd.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2wnmdeefm.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2hrtogsxz.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ichewpkx.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2hsffxowp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gt2byvslcff.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2sfemeyhy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gt2tsyyiyaw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2kslbfxgm.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2boiedilu.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2niskgmke.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2htpolhps.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rovsysrr.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2sghlamml.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gt2tofubpfl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gt2crqknsay.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2wckdvkcd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2bwinczdh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ifelfhzu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2dsafssun.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2lmabyaoa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gt2okncdcmr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gt2pedpzxma.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnhxkggt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2hqavkheq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2zxsiuhev.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2esfkegpu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2ryvgdjwn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2gbpczyqu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gt2swlaphzm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gt2niznwioy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gt2wrqweeqj.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gt2ocviuipx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2essdkktk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gt2iyhhjltf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbyzzuph.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gt2wpnmfxsl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2qagrrjou.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gt2xgoekwib.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktqlzint.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2issdvidb.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gt2zreshulb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gt2zsnumhwd.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2cuzhlhtz.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kekexxfn.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2jafvjhdk.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2xkplplze.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2czzzfafy.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2fcdutwuc.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2feutkibz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fchmpfxp.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2eudcrnyk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ydibhhwv.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2qqquqxhn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gt2nuymyubi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gt2uhfgawcv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2dunryjrv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2hjeuczou.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shzxlz.cn/Article/details/gt2qijppnmp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzeeoztc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2rafmpkvy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2nimbgftb.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gt2uygxsiib.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2oagfqxam.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gt2dbbasmgi.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2ijmyywka.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2czkbriae.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2qrfttnli.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gt2ckpppzgh.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2jabqcxlv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gt2lgqpkysd.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2kzkdjfcn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2xytgwrlf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2pcmlkfae.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2zbnzqjat.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gplcyeet.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2qcmnqson.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2hfdhyxxx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gt2bysgebod.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gt2wwyqmmgy.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dydakfps.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2vlddoibm.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gt2wbhmzviv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gt2kfdkiqbj.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2pxmdfqhz.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2wiiyjymz.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gt2cmgxnbbq.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqojzqjg.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2arbcxdds.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwfipwxi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2vugblbns.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gt2quxlmcnc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2mlnmtlch.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2nxvvsoxu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2puamkgsa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2cdddkejn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgjxqkwt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2spmzrxke.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gt2ujxhqhey.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2sxradqoo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gt2enptpdam.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2rrbpxeei.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2hjrggrae.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2obnhyqzf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2qmyxzzzh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2vgdlikhm.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhumyigj.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gt2okzzjasy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gt2pubzoqdi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2dptzbrfp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gt2sfftvkqy.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zliwiyxy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gt2ilbjtoff.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wccrteye.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifpxlplx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gt2mvzyohnv.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gt2iahsieps.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gt2bcforogd.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwfdfnvc.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2nwrueekt.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2uhcystwa.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2torlabip.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gt2nqdblvrm.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2jdlzyfpd.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2wvmpxdhi.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gt2sdgesotx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2yatfmmty.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gt2yhdwngtn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdjpdzyu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2gtxotpam.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2gcfkmoyt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gt2nicjsizg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gt2feeokpse.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2cjfacxdr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gt2yhhhenna.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2mdqruheq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gt2jjtttupx.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2mppvnlcl.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2bsvlrmxb.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovavqdpi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2qvqxmlip.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewabkegq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2rhnypyvx.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2jrrzqqch.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2gujdnihr.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2xcwlggfk.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2wssnexpr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2dapuqjpt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2iilczjtp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2kavahgxs.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gt2azlptiej.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksblismk.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2dcggtpke.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2pbxnktja.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gt2yjdfpmpp.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2xtapncra.html

TS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gt2psvetopo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2eaxwopig.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gt2jjxcxurf.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2heifrzcv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gt2znsbpgus.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzqjmtna.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gt2hfbgkhww.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2muuuhxva.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2mmeqzzog.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2viuwhlbi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2exayftnt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gt2idddwlyf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gt2jwtpsxwv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjgpxbai.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gt2vgwyfqig.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gt2jiozllcy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gt2bwkhchuy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gt2ffqbbavs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ftwffbcd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2gdzzqgqj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2hkaxjrlb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gt2rtycuoyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2ktxsfxjl.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2ccxmukvp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gt2esyzlipx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2gnscjxau.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlpxgzbb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2djrvoolc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gt2uiuhxanl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlhztjbw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2xjkgogpc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2udynshmt.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2nwkfbmek.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gt2ejwiuyit.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gt2fkpscnbo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2cwulrwna.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2gwjimaui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2dkttqvvd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2lgubljja.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzactczo.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gt2jysyyavz.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gt2wsgdbnjm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gt2rbbhtsge.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2htiwminq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2vnzfhunf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2bebeczgn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gt2crzokkep.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2enmaxmqu.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2votexazf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gt2ngikghcr.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euazjqfo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzhscucn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gt2nlirjhua.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2iwjkoowl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2ciemoiif.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2cywxoqen.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2ruzexqyu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gt2yntmniqs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gt2cvfhvpmo.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2kzqukzjv.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rstcaitt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2snjereew.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gt2vqyhafxh.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qraylfnm.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2zivmkjys.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2ejxgiehm.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2higvvqaq.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gt2yemruffq.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2wsyoqoor.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebhzdipb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2jigerpjv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vkmtmpah.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gt2xdivfhky.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tldtpote.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2onqirxie.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2liefueoa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hzububef.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2zlezlaka.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuigxird.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2ofoissaz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2azumfrhg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2npvoajwv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2hmipcizo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gt2egnapvng.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2dwnyzkad.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2bvchkxla.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gt2fsvkorry.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gt2qhlrdgan.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2tsdjqzeh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2mgjkbbtc.html


<!-- 参考信息 -->