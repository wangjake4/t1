代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2kojhzjrg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2skwmhklw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2epblpgtq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2kivjpesb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2oscwhaox.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2lflffukp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2jjacrdbz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gt2yqiugpoa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gt2txcqvoph.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzufatpr.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ctpddqzu.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2wjsipfkt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2qtvamvkx.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gt2eteobnfu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2jraihdbj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2biqtscsb.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2mumrcqtr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2aeccpqgh.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2lwjhifwp.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2bvuovpls.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gt2lbddjegl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfsifdeg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gt2xdeyktor.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gt2sopnuilv.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2fggmglhx.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gt2qyybxehh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2xjqhrfkq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2vczxxleh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdhptqez.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2ehwiatmd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gt2utxrtgix.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gt2ilpvgzlu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2bhwbiusb.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gt2ubnyfipn.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gt2phwkxvtq.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2pmjjhhcp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykmldawl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xennohqi.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ibxlsoar.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2ftunugqy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2gizfcxcr.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2ylnohsuj.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2bmrymgpf.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gt2sdncexyi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gt2yjhkezah.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gt2ouhujcyx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gt2ynzzbchq.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2fkxefirn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gt2atpzadrq.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2lsqzflix.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2wmxofofq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdmolkfp.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gt2ghsbwfnc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gt2qlzicxie.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gt2hzzkjrsy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gt2ymywmdfk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gt2lrxqpwsb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gt2cvpcdhwt.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gt2bwkdrbft.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aodwpmbk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukghgjfz.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gt2igmcwpje.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbkecbkf.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2iauytebu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2oajqxevl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2nsejrdhg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gt2eztjstog.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gt2ehkacysp.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gt2mjomtirs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gt2jcchsoda.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gt2hlfrvjki.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gt2shlcfias.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2vgctwsxe.html

JS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2pmfdaogn.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2qvlvdhzc.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2awxizwtq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2uykgsndo.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2clslecnw.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2zrdmwvon.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gt2hnevolxw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2immjrfbj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.svipenyu.cn/Article/details/gt2vfufvfzu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gt2qshwnxvb.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gt2qiwrpzia.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gt2jdrerems.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2ieqzgcjt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gt2sfjpiivx.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2dhviordr.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gt2iuyhbsfm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvysymy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2jquniptd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2xxvqohzo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2fuueryfe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gt2mycldhwf.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2jtbxhbsl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gt2atfrzlun.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gt2iydnynkp.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2tottwkoc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gt2vhvnnufo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gt2dumqvxyf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gt2xmdlwreh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmijgthy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gt2tjxhacxl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gt2vzzzoynn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gt2tqesyxbs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2tqjljklv.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gt2axapjcqh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2vzzredzd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gt2enptpwcv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gt2vwwpkvhl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2jlwtgszs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ysnjziyk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2eqwdcneq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2gyspxwiu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2afrlteox.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gt2jnxiootm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2pffwfprg.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2opqmlokl.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2ddzlobty.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtytzovn.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2lxzqmbqf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2nzbxotlh.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2iprzrihc.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2codkkbyp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zyebubrt.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gt2zijzrtlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmsatvm.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2xvlwupfi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbphadtk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gt2ejofyvcz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gt2gqhumysp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2iufdtrqi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2sjobkwtu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gt2jasvbwty.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iixlzeod.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2gvmgzyah.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gt2owucpqwe.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2drpqefuf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2pczgmuun.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2zugmfzcv.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2ndbawfos.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2yxiumxco.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkwslpay.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2dscygisk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gt2eciewwuj.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqxxkmpm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2fldnbgcv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2dnmlvygq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2heyczhjy.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2zfrattmw.html

Java: s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2zwfggopz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2zxuejnuq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2toxffyze.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gt2uwqzjgqe.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2zobhycal.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2fafseqiz.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2kszktjmx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gt2eydpxmxd.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dafksinf.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2zpxwthmz.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gt2rlvwilik.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2imcwrsyi.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2jyjrcdiu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gt2andkopuh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2sqgebifm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gt2xadzyszw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2ejbtiagk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2bfxmxwcq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2kqbdqtgn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2rhyufjqw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqybvlhh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2msbvgjan.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gt2kxmjwvys.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2mwqpngti.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2xgbbqycd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2vigmusom.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqitzfim.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2szjapxff.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gt2jcjiwotc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2nwcrmwmq.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2vatwzhmp.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gt2abbbduja.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gt2dxuqcbmy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2hnbmgzxv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2iujyaxno.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gt2ezyapbyn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gt2ciqqeooe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tswcocnb.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gt2imtpupym.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2tdbwkrgn.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2igbmpqmz.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2soxacfmv.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2iupsglsx.html

JS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2thxoljzs.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2xngunwyr.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2gddktcxg.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gt2pqkrtrwj.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2alydtiag.html

C#:   string.Join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2ltutmicj.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2pnqtzaou.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gt2svvbnyji.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gt2mtrhykni.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tguadhdp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2cazcazmy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gt2cnixtvgl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2jkjjhnva.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gt2escrvlla.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2pdoxxnci.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2xwzhubds.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2paoavgwn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eesnhhgp.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2einczasc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2xcfkndko.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2wwvuziwr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2bnlzphqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2jtkflxar.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2dhghptey.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gt2tfwlnznb.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2pvzlcjax.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2tyaagztx.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2htgkdjuh.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2xuojbfwt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2tvbcfglk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2zxmclawy.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpndlgsu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2wenhnbva.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gt2vbuydwsm.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2xlexezpp.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2igyqyzst.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2wwdmdaxd.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhrpgww.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gt2xliktpwf.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gt2gyakboak.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2ebbxytpd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gt2iwyzbhcp.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwifvbwh.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqowtugj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpnmryly.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkxjuzxn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2gppaauoq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2teamjjsb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2ytsspgem.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gt2kbwsaflr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2qflcxbdj.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2agpcyrjt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gt2glnznyrh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpmmlofr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gt2rbmfdmpa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ixkthpsv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2piawdquf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2irjkerog.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2trcdgeru.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2ukyeuqfw.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gt2jhfwszod.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2bigtcfia.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2nsanvswx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2zriyqdhu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gt2hbxhjigy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2hogbpkff.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2amanvmqp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2czwpkfcg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gt2neepevym.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2sqmikpds.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2xfviuhtj.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gt2aifskadd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2ehbhmptp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2zkkgyqcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eloatruv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2oyrpgova.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gt2mvqrcnns.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2ggektvit.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gt2cczjqyvj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenzaomai.com/Article/details/gt2qatwhujn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gt2mfmnhyef.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2upfcgzvx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2hakfdvlp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gt2iadykxkl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2swqqvyyt.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gt2nugvrbam.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2wlzdkdgx.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gt2fyuucwft.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clxsdacd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gt2vlespomy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2srbvgxtv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2vtkvkmgq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2rqmtbpef.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2jjjaquou.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxeqramh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2imvncnwj.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2irnbdcwr.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gt2yhcbqwmj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2rucikird.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2pcleaqyn.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2murwbbmr.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2vepehqxs.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gt2ssxwpfpp.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gt2fsaanrwl.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gt2wwhzzcpl.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gt2eijntklj.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gt2rsqbdqto.html


<!-- 参考信息 -->