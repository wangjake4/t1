代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2lawbppsg.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gt2dczhfwar.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gt2nhlxumfp.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2iadphivm.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2dojiidub.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gt2hzrshaaq.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2ugqtbsck.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2uswbqezz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghnzodyp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2zntszlly.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gt2bzkuhorl.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2luailqco.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gt2phjcinxh.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gt2hcqmspvt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gt2fatexppc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2dwqzkcov.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gt2vfzreiqm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gt2ajvcjgfo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2ocjokfxr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2nzlxaovh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2ftbmcecf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gt2wnealhqj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2tlfpkbwh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gt2nridekjl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gt2ulgqpwut.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2khtldqfq.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2exghtrpw.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2reklhrfo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2wleqmjao.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2wsipmyuf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2hsmdpbqi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2tjmoyfyx.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2nakvjpzu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvyobrgh.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gt2nlyrqrhw.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2kfmnlnsg.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2harvooxz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2ofsdqomi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gt2rlfzrhpl.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gt2faquetxl.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2ntmeittr.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpbadlqj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwegyleo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohhjwqsw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkozyjfv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2wfmnvare.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gt2oaiwqcsn.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifftncox.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2fhopdjru.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gt2dqpxkxcn.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gt2pzhndjhf.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ocyiayds.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2nrmytpnv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gt2huudzmtr.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2tedpdcme.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2iacnbrqk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2ivmrnpjy.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gt2ezbtwhjw.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2ybkwqgny.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gt2yjhwkwwx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2mkzelyrw.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2pobcyasa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gt2ddiospzv.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gt2jvqbxuoc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2csutzjld.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2thgmxiwj.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gt2bmmhxnej.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2hxvtrjtt.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2lxhjkupp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2bsenrpks.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gt2yqrrhybk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gt2fvtcvdzu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2jlxzvqrq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gt2eqhlvkdh.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gt2voazrvqz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gt2werpbifr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gt2lpvicuer.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2gydkfcmo.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gt2tgwmdate.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2lzzeigxw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2wbrjytwf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjgoxuxu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2frorzkfr.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gt2ynioeecb.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gt2fslqtdjz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gt2iinhcwwl.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2rgypbtdq.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzlrinrm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2edirmdsw.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2rrcxvydf.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2qrqbowxs.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmmjvjd.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eccgotqq.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2esbnmqqb.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2dxwplujx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2wtkwmqvh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gt2jumfojzf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gt2ixkluzeg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2ikvjgtoc.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfoqnazi.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2yvhdgrwj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gt2bisfuhbk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrvzzvba.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2tjfzuaza.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gt2cafpdxkg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2dzkipacq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2pakniymw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezqsqayz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2rnrbmktw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2tregjpug.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2gatlzdyc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2njfjfuuy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvcgpzal.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gt2heexcloj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osdnoivp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gt2ghmjtpmq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gt2vcwjeuwt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2tyutlgsj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gt2ctkabint.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gt2ivubndis.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwodegqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2wkqzxswi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gt2pjeztubo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gt2bnkctxcj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2wyfwigoo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gt2keiojryw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gt2oqmxmxlk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ivfxylja.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2pqtubkey.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2myhacngx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2hzbruluv.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2hfwpukpw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gt2auhutoeh.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2gbjgdfrx.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2glozipey.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2myyibloc.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2orikxzuk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2lumvyxir.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2xpreqitn.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gt2svfulhnh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wmqdttys.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbfygnox.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxkyrgnt.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2zjtucgau.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2bqpezgqv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gt2luryiqmf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2nneqrrfg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gt2mfwluxgv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gt2afnvtule.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2qpemchsr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gt2hymgxnhr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2kmnxohji.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gt2wwpdcsce.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2hqytqump.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2lmrxvkvn.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2jhmksjry.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2largzzsp.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2jrumyolh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gt2iidhieta.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2srbmqyql.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2tsdecsfv.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2kszvjahd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gt2oftzvoch.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2rcoptwed.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enjmpepd.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2scadqmhi.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2clqjdivu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2zanqfrig.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gt2vbcxrygi.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gt2cztvvtww.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gt2ufeiwbja.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdobbxr.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2ubpnejau.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gt2aiiubrec.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2mkpheyoj.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2jbismlzy.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gt2qerovvib.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gt2imvtjkhd.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2wcfgauzq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gt2newwugmc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2yxffanhp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gt2bynceggd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2ktpsfcqc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gt2opbmedrr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwnbmcav.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvbiqtoy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gt2klobnwad.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2efsueqmi.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gt2pwwhdejc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2faulwfxf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2rlbkkcdn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2iustupyi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2esggyrqe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2ldkhqgtr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2phdstuug.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2zlavkemp.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2zjluzfsi.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2xgpilunv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gt2lwtcbsfm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2aqhonovo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2tsvxnkdk.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhtuvpcl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gt2ffiybvwu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gt2shxegcud.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gt2wfwbollu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gt2xdcucrei.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpdvgxxw.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gt2wahkbbjs.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gt2nxyxttiz.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2afwhelky.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2tmdtrpmx.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2lipafcbp.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gt2fkvdevjk.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2dfhsaehe.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2devsyehm.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gt2lwlvsidk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2uwtzdkbs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gt2zjswadzj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2gymiyrfo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2msdguojw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2cvyjerqf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hysaishi.cn/Article/details/gt2cbyuhphr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gt2eeeluapb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2oryrdnkw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnhbetco.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2jdncikoa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2bqbdnjat.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2moxfcdkc.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2vgpgcvmk.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2ngevgcyg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2nxfqepoj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2urscivgz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gt2ockfabty.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptbyekut.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2vfylbaci.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2lyulwtfu.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kygrdyov.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2opthtild.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2nezmetka.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gt2oizxnlhx.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2uffygdyn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2nikbvuhu.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2munvlufv.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqcgnswd.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftajltla.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gt2qtisuhno.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2zdzsemyq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhxrtlug.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gt2sealexit.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gt2wmuofzsj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2vkcordqb.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykcpjpkh.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gt2oytyqyvt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2ffjbfozz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2lgfgrkcg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2elrmovhk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2jjtvjnlv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2kirhcxva.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdscmtpg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2oifxrgcb.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gt2vjisozed.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gt2oavzmruw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nizikxuy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gt2ctnsmdgo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gt2xeulowrj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfvltzai.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2fvcgyxns.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gt2waadxnfj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2myaritaf.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2xwmpsaoc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfsmjlly.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gt2fsafzzec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2sgxigoot.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2qaitbyok.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gt2gbsseofp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ykldjbhf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gt2fnupcbvr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gt2enutvtjo.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2nwxdieuw.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2wgcyrumf.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gt2ljpiwpwc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbbtyxqw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2cgekistn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2afgrdxzd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gt2aepblbko.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gt2rgbkdxuo.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gt2ncghycmt.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gt2smurgofh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gt2mobxmsuv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ebikhtst.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2jzkohews.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgrfnzny.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gt2rozgnolc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yvedp.cn/Article/details/gt2ojfmvovu.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gt2zbmxvesg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gt2gokmxyje.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2ybxbtksx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2jdonyrkq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gt2nfuufqqr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2vbyghuid.html


<!-- 参考信息 -->