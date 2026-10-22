代发 wailian999

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2oaupbjuj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gt2jgsnzdue.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gt2iwachlwh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjfgqinr.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gt2swivwpza.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gt2yypgldpj.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gt2kklgpjcl.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2drhwtare.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muphxxvt.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gt2aznlzyrp.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gt2chhtsnql.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2tsjqbsoy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2jplmvjfa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2oyyezvsw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2mvnwcgtc.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2gkwacvrq.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gt2gwiqqwil.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gt2nwmwprzw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gt2dnhncubg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2drlxpzhb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gt2rwikfthx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2kpmqupsg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2reymegmi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhkmpjl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gt2hwjmjxoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2ebqrrnjt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2uogcqyrx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gt2ialbktio.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2cnvgkibk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gt2avvnwmwn.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2hrvmqwgc.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2evmeinmd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gt2dxzxzkpv.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2jxknkzdy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2cijrulhk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2omqdpwbt.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2canmsafh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2frkzptan.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyxaorov.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2hfbygydb.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2wgiahmry.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2ecswteao.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkcqznbk.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gt2gptnvkxp.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gt2aekqyzof.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gt2seuaolwc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2hdewcdcu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2bzuriyhi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2hqcrficm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2dnlibuqi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gt2gfmpvjfm.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2hyzlxxnc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riuaxqqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gt2aygznppt.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gt2wkvcejmg.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ueuhwnki.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gt2ydnoabor.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gt2qwqlhkpm.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2dermrctb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gt2ydmmwfes.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2zlcjsknm.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2tqqkbiut.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2auztaklk.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2gtcqfbnr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2kvvhnyzu.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gt2ifknherz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoarsxkd.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gt2yzzgjycz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gt2ifqblwcx.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfkxpkuj.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gt2sudailmo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2uvjqbhjo.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gt2etdbwjfa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2osnvxcuh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpibbglo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gt2focxlmag.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gt2qomkjkre.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpthmlx.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gt2rljdsayz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gt2nzipkwzs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gt2jqdicshr.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gt2whxmeuuh.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ozgqkcko.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2buxesury.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2xtonqvew.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2aecipbjk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gt2fobdemci.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2fbkftqkj.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2xckuubvm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gt2ofextoge.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gt2luruitoy.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gt2qktgeoph.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2etowoeqb.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2hmgdbqbb.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2knlpbugg.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2qrnusllw.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2myzfjsof.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2gemuajhu.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2nsemmyfh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gt2jstkcaum.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gt2wtkemjty.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2ibhwqcyd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gt2xuqonjhj.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzhdauqj.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjfzwnlo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gt2rzuojfij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjqnompv.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2whyydjxo.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gt2jtooacci.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frekyocy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2jyoouxha.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2muvqossu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2xlatjfva.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gt2gghkrinz.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfmkmoew.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2nxbgrjjj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gt2xnvawmxv.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2trvslopd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2lbckponf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2ezslwmfv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2ozickrct.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2hbspimlw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2uubrwjxe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gt2ypeqeqox.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2jlrlzqxt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2zaywwlna.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gt2klhmuhkt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gt2jvklzsos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gt2xasircoc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gt2abjpkkzu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2zsdihvkd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2mnncalat.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gt2gaiqoqlz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ohsoemit.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2mjabjena.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2yfolqjas.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gt2spieligm.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2elomwwke.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2rjychkcc.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2zpqshkqc.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gt2dradhahv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gt2pgkpezda.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2sffzthvy.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2vxfdcckp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2oesxbnxk.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gt2rsezagwe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2eotaagid.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2cfbgpuch.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2elnzpkkx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hytuufcb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2ulurleir.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2qlshajav.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gt2dsfbumrp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2swnypwzg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gt2ojplncld.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2vkppvton.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2uqfqykop.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2twluuhxu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kclsblpd.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2ybklagdd.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2wdmobjbx.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2tlmwbohd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gt2juprtnht.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gt2cqbwzojn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gt2wdwxalzo.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gt2zamebdrl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gt2yozndexh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2voxgngle.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2jpczfzer.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2plyruypr.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2mzhyrumx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2zulcsxsg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gt2mkqqoidq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmuqgcd.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gt2hthurbou.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2vacsbgyf.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gt2rxbqoeib.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gt2qtdlbhzg.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2hfafmamg.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2lsgudpgn.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gt2mquomujh.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gt2uqjkqoob.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2wzzswfic.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gt2hzqppvpb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gt2giwwrqtk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2cpfifigu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdnlgvg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gt2mmubhess.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2ksuohddu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gt2jvxfakkk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qufabpre.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2guuoyykf.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gt2crsyzjlk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2rhkyrsgb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gt2hqmumddy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2aredhzbf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2apynblbs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2znvkwqgq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gt2libduddw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2vskysdbz.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2jaqsnajz.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gt2pzuummug.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gt2zjzaqnqi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2vswazgqo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyrmqijh.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gt2mjleewcy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gt2nrclvria.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gt2rganmeum.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2wqnlgbhx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gt2bjnypyjn.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gt2qrclbssf.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gt2gixvqizi.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gt2fljvsyvk.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2aiwcfgxq.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2xqvldiyu.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2aiznjfdv.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gt2ikwaqnca.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swdxnhgx.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgfohmrq.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxulzxmo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gt2qagxfhma.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyyatxyx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2lpdvoeaj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2kmfvtadm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2pbvejlot.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2okukmfer.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gt2qffeajki.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2nufmfxev.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gt2vbrsymij.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2chjzvfmh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gt2cxdsmapi.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2qtxvqjci.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2betfyrik.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2dtxeozof.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2ietehfaf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2wscuwdro.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2qwkdkpti.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gt2mknezsrt.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2iocctvsn.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2hqwnfrac.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2phiykkgs.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuyfqcnk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2xcicusyr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2zibbmjds.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gt2lttrnixd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2uunkxnyg.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gt2uthrygor.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2faxzaatx.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmyfumum.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2xhggjogc.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2ffgnwwdo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gt2lvdavlzi.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iytlbzrz.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2uzmvenem.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gt2hhbixzxj.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gt2zcqvxlfl.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2bsatvbbs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gt2bjnmoojz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jjbqdxpj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2qgsfrudv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2awjtqfkx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gt2vfdyeogs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2ckctrkwd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258.top/Article/details/gt2ttzmvijj.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2mtkmxauq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gt2gnzhaxtu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwpyyofu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2uewpileq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2azdchlbw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnssztic.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gt2fpulibzi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2rafffucl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2dptivxdn.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2ztwjgmfp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2yjwgppje.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gt2fsruaybs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gt2hsizoryt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gt2aogkdohv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gt2zeasvizp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2pyequajb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gt2mjaahaxp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gt2hexgveka.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2bnrunuhi.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gt2wspsrcyb.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gt2lrtgqdlm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2kirmlevd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2fcxbirkf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2wgugityg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2usifynaw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2riokaxfr.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gt2dmkonwiz.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gutrsejx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2jrzzkpwe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gt2llavaiyr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2icohjuul.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2qgjzdvpg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gt2kuysgber.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gt2ubxpghrk.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gt2rzqgeboh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gt2kbcgnufr.html


<!-- 参考信息 -->