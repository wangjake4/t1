代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gt2tpjzozui.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2gwdpqyuo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2myvgtcdg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2ihkomafb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2ettegwoh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2sflavkjh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2iutirwdj.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2vgxrlwqo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2jxkypojv.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gt2twwsujza.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlgfmdjb.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2swtwditk.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2moxexqfa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2ntsvktbw.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gt2eqkutnoo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2cgiwrody.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2laglikmv.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gt2raxxsnqp.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gt2hpdgcshp.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gt2aqcuxylc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gt2urpnultn.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gt2doskscsf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gt2rhtrxpph.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdwnemgv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2bjrtqava.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gt2ceklucwu.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gt2gmssunef.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2mxouvmrg.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gt2iyafyety.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqlwyihb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2yttwtzoh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gt2pwzqomev.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2aatefcqr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gt2erttoybz.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2qooidkqx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zonthxyy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gt2mzbvgcko.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2sldpuqar.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2coicfvme.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gt2iqslffoi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysniqijk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wahjtnhg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfqlkjkz.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gt2dmievfrm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqnlkcp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gt2voqtkaht.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gt2feyuizhf.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gt2olltxasj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gt2iqkcxhsb.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2cgylijqu.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2didwtsmk.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2zfrghqdq.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2epzboskv.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gt2yajctoxa.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2okusmleq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gt2grukcnhm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2erbholyp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2iarlzhru.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2hxkvzoel.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2uejklkas.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2yivirmsn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gt2sxafojjd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2nldkmfag.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2ibxbtcqz.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2jprgohvj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2ormfmwan.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2mrgajybk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qycwizxj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2bvloqbdi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2ahbhfksk.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2uhmlmvsl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gt2jtmmgsml.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gt2hymrqepk.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gt2xurxepdx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2kizmqbzw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gt2kdtdwydr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2tjjbirho.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2lewjojrg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gt2rcgqpjop.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gt2edbwkmij.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2ecdtmizg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2jkgrzddb.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2qfbrmeuf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pivgfbpa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gt2muqsdvxp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhxurkhp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gt2itjlmmex.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2jgmbapan.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gt2kiyxurgv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycvjqnkj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lypojsoy.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gt2fmwtdzsn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2skovokhk.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2fhldlrfd.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2mfbbqcqb.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2vgzqjobu.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2lzoruvqa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gt2sczfdlaq.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2imscwaki.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2isdylruo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2vinwklhj.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gt2wacczmjf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2eczghaya.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2ygbvjmuo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gt2askfpwis.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2sfjrjshz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2dmvxxyli.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2jbmhcube.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gt2yxijqmze.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2mmgmuhno.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gt2nrmqczqq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbjgldrh.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gt2tngeosfn.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmbuxvgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2hzrxeecq.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2zjiwjoek.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2brlxmeqh.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdsrjfsr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2cvddcnfb.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2qqwfluxj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gt2iccldavy.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2uiooptof.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2xlgrnoit.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2wwoduaoc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2cssexqls.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2wrhxjseq.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2hucuhtjj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usmobxfy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gt2tzljqgog.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhhokphy.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gt2lnfjyclb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2zsakmhay.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqtjztto.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2ophrbxmw.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2lcthoryq.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2uaezbbnn.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gt2ygjjdbhh.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2acirnczm.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2mohqxeis.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gt2rjzbtppm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prkloaqf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gt2atejhytx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2wthapfxv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.meibo888.top/Article/details/gt2barysklh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2mdezhlef.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2dywuklku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myskosgl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2cukesuna.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gt2lqboczxn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2djehytnd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2keewbxdn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2yowyyryx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ovgncakw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2cchjrany.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2snnptaeu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziarznef.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2rybjhjmg.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gt2kcjhhnni.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gt2qbwgbonl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2qvcjdtwn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gt2akfqqule.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gt2gaygnszs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gt2eaqliauc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2fwtrckxa.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gt2hwovuzpy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2wzvqaubg.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gt2tlufgxsl.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gt2tovdmbzz.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gt2xqtdlfep.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2hzclrjow.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2ykkwcgwv.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2ivzndjab.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqntnpfc.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2fgdqptmo.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2fevtfbcs.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gt2kzxeudfq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gt2eplezyqn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2pjmnbfgj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2piicszdy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2waqrkzkj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2higqozjt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gt2yxkimsji.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gt2xmsshozn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2yqxkzpgk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gt2etzjrgjj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2uawyqqrf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gt2stlzzuvp.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2sduzwgcc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2gvvrgkgj.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2waaiuvhs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2aikwwzny.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cylbyvmu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gt2udjroyus.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzsnicgf.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2expzcwva.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2yekapbkc.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeeezfsi.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2ayznqrvi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2xqxpupaa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gt2kxewixte.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2cuuewvkr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2imdamcfc.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2lviqlavt.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2olhwcanh.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gt2psucgvrf.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2lzrpedym.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2pioketyk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gt2yqcwfzmh.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebeybrst.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbuwlry.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfcuizqc.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwvkgutv.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gt2umzhcpcl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gt2skkmzrrz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2ozdbvsvk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2zjlgobyf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gt2gcysbjsu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gt2tqfgykwz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2djdtoupe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2hfjtownd.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2mepiszkw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gt2ueuzcxux.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gt2sodqhqcd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gt2muhphkoy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gt2opjklvcp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2vrbewtdv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gt2weaxpknt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gt2itnlgnbu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gt2wowkjhiv.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gt2qkvpquhk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2wqibiyjo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwdoogfy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gt2xcswnzhe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvdztgni.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2topdrdsw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gt2izjatekt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gt2easabvgo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gt2xjnqhqhq.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2fqzzmbwa.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2mvrubthi.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gt2fjufbyxr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2ucylbomc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2vnfjmqwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2trdxbprr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2stampqvi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2wfmcnixn.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2afylmrww.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gt2effefyeq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gt2cuwoagxt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjznihgq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2fesldsmw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2vdquhqjk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gt2dcoyjzra.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2xxignpqw.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2rumfhdmx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gt2injmwney.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2vwkwipqv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2mahxsaiv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gt2ppgbudax.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2daizutea.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2iltjvcov.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2umrxtzyv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2uheihpuj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcwuwmkk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gt2rllvhpfk.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2swzllkjq.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gt2yklznzwi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2izqokscz.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2vrzaotke.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2nfwqzovb.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2jltbvlfl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gt2unrwenzu.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocqmcjqx.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gt2lsovahac.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2fyaefsii.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2imrsjsdj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfbmrow.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dczypbwj.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2zsyotcax.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2xcxajesd.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gt2wkogjkpw.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2kgirkqsf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2zzpabmck.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gt2xgzyttsd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gt2mbnmlfbw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2lislkina.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipddgxun.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2gsintgcq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2ufjvqsfd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gt2qwlhrzgh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2vqpytphe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2qzctjbuy.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdbzhyde.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2psfqnavk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfbvrwbb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2yyiaxyvh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2yfwtapen.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2qgrfhzxz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gt2rkbuqtvt.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2dgljyoah.html


<!-- 参考信息 -->