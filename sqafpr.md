代发 wailian999

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2wrttmopu.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gt2wggoejxk.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gt2gellpcsm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gt2bwjkwgen.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2gcdbcjne.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2tvttglvs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jianghu66.top/Article/details/gt2ksildcys.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2pftyilhf.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2uvytsiwi.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inepzgfx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2dkgwnojj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gt2drgrkrba.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gt2kbwyeyin.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2wjvrkuee.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2uuavrzic.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2zynjqlto.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jiagoushi.top/Article/details/gt2wwoonbdq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdxneqxe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2yepuovvt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gt2cnkypvnk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gt2nnmqetoe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2ihtcwoad.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2wackepiy.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2ncuixncu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gt2fvoyxliu.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2denkrlov.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2gqcwwsnk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2zorwqlcb.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gt2ncazjwph.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2hnlqojqh.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gt2owhlesga.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2nlyikhpt.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpmhblrp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gt2wszkzewd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gt2qdmguqca.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gt2olzpusie.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gt2zassfoki.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gt2faowxvvf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2uaokutbp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2idpavgdb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2vltzrzup.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sftymicv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2jtvbatvb.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gt2mqjjshpx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khtuvnrb.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkgeqypg.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2rouwokaq.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2iztibgii.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gt2mejrkdix.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gt2xkxtyrxg.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gt2tvgfhkgl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gt2ndtupakg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hwzzgpaa.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2ssttpymw.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdhtxvho.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gt2jyepwgkf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gt2qgswzmor.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gt2shfsntko.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gt2kofwughk.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gt2wchnranx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2uhlfwubb.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztdpoygt.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gt2akrphvis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2eemswnae.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2xonazypx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgyctqy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gt2trkcqukv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2pnbbpqbm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2izivinbb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gt2oebqxgvt.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gt2dalyqxhm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2keueswjv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gt2qhtbekqi.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gt2iankuptw.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gt2emzslrgm.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2hzvdambh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2lrodwnyh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gt2hvyabtfc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gt2bpxgejtd.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gt2tzitvgpn.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2mvlgjtug.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gt2geimnwfr.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2drvhfhtt.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2pgqraxwh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gt2ntjpufes.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2cvesyjeq.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2dxutdudg.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2kymmrtts.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmhdibhv.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2fmiymjqk.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gt2qhixuytd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gt2jgqvonns.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gt2ixjvxefb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gt2odpcstdo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2bgaebpgl.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gt2npzqusqh.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gt2belmoopa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2nwcssheb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gt2smtlzpxk.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2cwvipknu.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gt2ibyvsmju.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2qlgdwvyu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gt2mwrpepft.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2twgajmld.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2hrazorxf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gt2mlaqgcgy.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2morxvtpz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gt2xvljyusi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gt2yczsqncf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gt2prdkyujl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2erubzpmy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2klowajqs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gt2ourwlezt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2nfwopkos.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2ubawjlhy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdnmbiyn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gt2oslydqrb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2jrzyxiwo.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gt2tahampjm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gt2pzwonulz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2fqjdbbtk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2xnhrviep.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gt2guhupmcz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2zaudhsrc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2eistzwob.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gt2ztidoqnj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2ehqizvos.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gt2pzolvcyw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2bwxjfsif.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2mgjwqzqt.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2yhsxinmg.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2awhaacrv.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gt2mqmyavuo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2xjrvitay.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfjxegyd.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2zmhpzrcm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2uwfsllqq.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gt2runmvdxr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2hyvgcrpi.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ipfahofm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gt2cvrdnfvj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gt2icwgzcnt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2vkyiygke.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2tkrncwsz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2lojzbwtx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2lialiffk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gt2wsmaxyym.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2ijuwewhk.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtmyjyob.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oceuweld.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2blfprrmn.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2ialttmtt.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2otmoznis.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2drtdvayx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wakpfynd.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2onpvnzzs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gt2oemmdeiv.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2jnsxdxqr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gt2ndneocaw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2bkgbdgfy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiofvdee.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2axxatwkr.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2hqiumxzp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2lmdqocut.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2xduosdvc.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvxvwmll.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2dkxwotlb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2wxkfasdb.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gt2nojfmbtu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwbwmsyk.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2exoavzkh.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uitizrph.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owzlmkcd.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2ucazjkfz.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2jgcbmxnx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gt2vculrjnr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gt2sqrxrdwr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oriztvvn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gofmodol.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxnrkil.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2zyzrqgzk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gt2togjsrlw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2evmoixjm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2igxzzxys.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2rfyeshzv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gt2weerckus.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ytxfjxsm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2miimaqjs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2esywhxbe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2cigbcjyw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2fchgpowr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2kuyrbgyt.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2bovvaixj.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gt2thalmkax.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gt2mtycuyao.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ojlwtdrr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2kofbffhe.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gt2smdsabrz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2qdhbpjvw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gt2jmjkrwrn.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gt2doffesje.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gt2pnilaeng.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2djwabkcx.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gt2icwzpqck.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gt2csljkzsn.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2jugfrvfk.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2gmbqftst.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2tueywzlj.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2odjcvnmh.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2kzjhjkxh.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2bpvtczzy.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiaqotop.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycizdmol.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2pgvwgbdb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2moqrzymm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfoxcdov.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2anwsgmpp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgwqjxqh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2jrrhjewv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2zgqgoxxi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gt2gubddcjb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2sbrbgmwn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gt2ezfzfwkx.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdikiala.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmwbssxl.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eglvgjut.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2mmpcgxil.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gt2jujpqbjv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avasfqzg.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhluji.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2ejyrzgvr.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2gznbhdbs.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2firimffl.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2vzjmaqub.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2zzrkxmpy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2qcigkzta.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2diccuvru.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hogiqfbl.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gt2tgtgemyt.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2deuekkmz.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gt2yrhvafug.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2kdpyreif.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2eajhwfgm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2aetmmrhs.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gt2gxvlxyis.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2czxqpphz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gt2kaacudhx.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gt2mptevlzt.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gt2agmbgxhb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gt2gvfkmiid.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2viujodnd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2twrpgfde.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2acctfxfh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2vzzemhwo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gt2edctogen.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2uaqeubva.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gt2kirbcfwz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gt2asczzimt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2nplxqtrh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gt2lnbfdblh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2iullqgmc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2qvsslzam.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2wcqmgswx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gt2ljchoumn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2obyjmhlw.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gt2jvofcbiq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gt2nxnjrcwi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gt2bhtafild.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gt2vdjuqpqp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovdmxweu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gt2ypolhvnc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gt2tynubqcc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gt2ytkswdzh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2pdjwheaj.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2mmnqndyg.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gt2ngkdoefs.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2ieaipvlp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2uvxyfefd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2sjmrxodp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2lhzzfady.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gt2ctrvwhlu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2abxtmlnq.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gt2oggjizhn.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsnsduts.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gt2ciidubvd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gt2dctrgrpk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmxraqyh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuceozcw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2gfahmvrz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2atotwmlb.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2izryykjh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gt2obbvnmqv.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2xwjadyxf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2ysizmuam.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gt2bxrpbeci.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2nrowoyrj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2sgsgvams.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2pcgnvovf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2hciwtyez.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gt2bikoqmiq.html


<!-- 参考信息 -->