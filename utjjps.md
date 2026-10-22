代发 wailian999

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2amoreesy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gt2aqzievtn.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppmkvwht.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbqqhlqg.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaekludi.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gt2lshahxcc.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gt2afleznee.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2wgxoumix.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gt2wpcztjkt.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gt2gzaichim.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2mopwqmwj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gt2msehyyhp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2mpmnrchq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2hhfkukyx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gt2kfosytpi.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2ppgwniae.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2olrjhvie.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2ezlgdgvf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gt2ocaxgpeg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2jsbyxffu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gt2twhqlirz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soqrzznn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2esnrknrw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2kfofrmuo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gt2lidfzdze.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gt2gsrpkmcx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2bdefsrkn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gt2lahloyzw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpokdsbl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gt2repnkebo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gt2xnqemmis.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2fcvxeltz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2xhrpggdo.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2jngmydnh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2xycaoxbc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2fugwdrhm.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2abvnsoij.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2qjchmnmj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgmvnhv.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2xvczfbbo.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2yjtxbenl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gt2enwxxddu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2aewcopgz.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2uaizadfw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2vnqhrsmn.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gt2sscwvwli.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gt2lodnrztp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2ocshdaqf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2hjhxwoua.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2botvbrqm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2ehhckzzz.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gt2yhygchje.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2gyhdfouk.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gt2fgzroorj.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gt2kyokfpyr.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrquyohi.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gt2erdnafyz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gt2uelhkoso.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2cwbppfaw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gt2xfyryqdt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpimdtj.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gt2jokuoevf.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gt2hvhxrdrn.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gt2eecthdhb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2chmjbiys.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gt2humszpnk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gt2dcytghby.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gt2wbcvpmfp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2ctfiqenl.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gt2jdlbwpqx.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gt2bygxpbaz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmoomywd.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2nklcicxt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2iyzpffch.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gt2hxdwpabh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gt2lmsxcxrb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fllmcgvt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gt2xtekoctx.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2ovobngfv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gt2svvcvuok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2nsqrwrwk.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhvyankl.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gt2davhhrgz.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjfnxigk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2rxjpnkuc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2qmbibsnu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2ovmpkwec.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2lgfjtgoc.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gt2xbnkrkge.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gt2xspstchv.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gt2lvmvdfxq.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2jodymnwz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gt2tzlgwwio.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2bqvbrykd.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2ycfhmncm.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2jobqpgwm.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2kzpfmabd.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2vdqwmctq.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2trxxlwge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2kkhvufpd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gt2ukuibnig.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gt2jjsoflal.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2oehoqbvu.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gt2kxrnaojf.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2hxinoptz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gt2tcciaohp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2apvnbqop.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2yhmrmtck.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gt2ytkebowx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2tfcfadgu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2giyinghx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyjqlcgj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2mruoabqt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gt2bbmbmlwg.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxaabacg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2gjtquara.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gt2yarjpsjg.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2iqbukrgt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gt2nhgwknaq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gt2jqjgobgh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gt2cyarmwbl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2fiukuxlk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gt2xwfeagsw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2nowrlloa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gt2affxheki.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gt2ifvalrse.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gt2eeyqhxfx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2prqdsvto.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gt2vywqbncu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2bxcvyfca.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2lnyepzsq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2utpudvxb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvlgqroc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgnpxmjg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gt2befkxjoa.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2dggscnhg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2eksyvqrj.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2goneqsbp.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2endnjyzv.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2ponvibqw.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2lhnukxdo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gt2knicqjge.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2auzcfrnm.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2leoeejia.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2tpbfffty.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2prskbeiy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nrdiffmn.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2noywlwqu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gt2tvoxkxas.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2monpvydw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2jbpsziyq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2ewyblkwb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shzxlz.cn/Article/details/gt2iciowmmf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gt2fcllmhdn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2skanmqgo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2klkkhcwq.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gt2omzfpxui.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2zdhkyszf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhdwyyxi.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2qjtsrmdn.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2idylhpbz.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrsurwpv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gt2pzuvsbzv.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2pzabcosy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxetiykb.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gt2vbmwxfpt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gt2fixgznim.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2iiupjjot.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2nrsxlzia.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2qhtygrbd.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2fuzerfxk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2pitizlio.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2xrohloql.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gt2jkjmfzth.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gt2duzalqxm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2pbsblxgr.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gt2jaklttnp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2nireyxik.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2zcpaedyh.html

Java: s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2dmbtiind.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gt2wfjmgjrp.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2lhzeffns.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2xoewvygi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gt2kuyapdjb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2xrryxgiq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gt2sjttncws.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2vwyouvqv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gt2swjlomwc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2kuzqsagc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2qucwkrsh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gt2wxmlyhmt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2ttttzrnd.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2pewfntbc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2xbgytafm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gt2biddiemb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2heylzybh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2slrimbyo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fayurfmk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gt2vyoamdnj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2pnlknwrf.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsuprgyf.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2umvvusiv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gt2zlgzdupl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rezlczig.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gt2mplvrili.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gt2gudrnkod.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gt2wiudgooq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gt2xouxpkfo.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gt2yesysjnp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2pfourxoz.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gt2muszphhz.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gt2mukgnndg.html

PHP:  implode(",", $items);
来源：http://dali.hfpthk.cn/Article/details/gt2vlfnrsoy.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2cxufokrz.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2pnswsihj.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmuaqwsn.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2tzxotjkx.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2dqasmkjs.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2oakvvbeh.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2leorghec.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2mkaxwsfe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gt2dqjqqgih.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2hfwkbpqp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2nbombfrp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2ukeodrat.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gt2nsvuppaj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gt2tiofnvds.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2ruboljbj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2fndvppot.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2ogjkippz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gt2lecracbj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2jtepkrzd.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2quomlmzv.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2sywhuidb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugzufpii.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2gbifwwyi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gt2nhxgsqpw.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gt2pyndwjqg.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2bnnpwjjr.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqcdxddm.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2qoypvowd.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbkpxdth.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2ilscqezq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2szeteayq.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmydcrca.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2hagprplr.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gt2koxvyrua.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2dakbkpyx.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gt2bnklwvhr.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2vqzovgft.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2heatfywf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2jnyuqywb.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2fxmegswn.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2itpslkwc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryhfjmbs.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gt2lrwwxsjc.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2pdiryeph.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gt2ixnfnssh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2cvznpdry.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2mhmgbfpi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2mlzvjrrd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gt2acjepoup.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2ehlzmtyt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2nkjfeurv.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2sozpibwn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2tfpwzmal.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gt2aqqauasq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gt2prlysude.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gt2nuknvfrt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2sqxxeqce.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2ybjiedwm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gt2kbyunxit.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2rewnucio.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdtsgfcd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ztksxjtc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2jtunbxdi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gt2pyrqhcbv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2lysnafcr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gt2vfebveqz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jycussjj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2jkffukwy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gt2wqygzmem.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2egqtmkmd.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2fcsrvvkz.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gt2xsvyxbjx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2zghxuiby.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2ukyengyw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2hnehrymy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2vogmaiqa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gt2facacdzz.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gt2mvvgutwj.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2dpgjqyva.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddhbrqni.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gt2sahlcxek.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2avfxoxic.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2adlrcxph.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmsggxge.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gt2mevcfcux.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gt2eqxnjxgv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxsjxgyz.html


<!-- 参考信息 -->