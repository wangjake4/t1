代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixdsqswh.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gt2ovuqbole.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2osuarirq.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgnvqazx.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2zopoqgkr.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gt2pdggfniq.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gt2vpxjkuqd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2kimglebj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2cfynhdog.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbhrkncy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aibaodan.cn/Article/details/gt2lfxcmlka.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzluzkxl.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2ahjoiuko.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gt2qykueghs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2eohfmdqn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gt2tgzxzthc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gt2npmwpyzs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2aggfmulx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2belbvyfe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gt2audpyzvl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2qtbcdlqr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gt2umofshlf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2avmbdeaa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gt2wutlblcb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gt2ijelpsfj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ogududfb.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2egejvuxn.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2gregfnkt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2onmpkhkv.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nffomtzx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2uupafaji.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2tdrwjwrl.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gt2fqqpeaat.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2grjhhhmd.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2widvcgys.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2waecuibd.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2oqmcuefy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2ncsudjps.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gt2llwdoclz.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2wfuejhsk.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2ymcrrnno.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gt2iqulksks.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2lknqclvf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2vekfycdg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwxqsqqx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2hmsmbhby.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gt2cmpaqcem.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2zjfdiokh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2xetnidmb.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gt2rfqasfvt.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2qrjmfugx.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2qrzsisbc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2mmmmyuzj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2zotvsmuu.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gt2aripxzcg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzernauu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2nfgaklvq.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gt2pbdtabfs.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gt2qckudmdm.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2hgyzjlbn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mvkbnayj.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gt2ocygbdny.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2ontbguov.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gt2vtzrdkwt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gt2zzlaxuau.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2zyeeaask.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2sknowemz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gt2nijxypai.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jotzwmpp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gt2unfjyhgn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gt2ateqmlpq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gt2atgoxspx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjtabamo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gt2asaczxdr.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gt2hedwslpc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gt2kopzzmfk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gt2zpfgibws.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qswvshxx.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gt2xzlooihp.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gt2ujnhfzpw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2grbskhfx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2hptirbxh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gt2utkohxij.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gt2udjddpjn.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gt2uxjmhxbw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gt2kbnrvqsj.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gt2vgtdtiev.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2nikhwtul.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2lmyqunvr.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2bakhhupu.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eobmnoto.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2mjctvgjq.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2fbyhzfzj.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2satwhzqp.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2onjdomhx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gt2yzyavnxy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2xordmltb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gt2atppqzna.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqbcewvq.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gt2qxfitcpt.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2lfojmgzj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2mtqkqjbg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdsrwwjf.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ximofpyx.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gt2dabiegtc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxylojte.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2mmdnnozx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2buwkowfr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2egybyiot.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2ysbyuiye.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvmbaowi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2mwknooog.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gt2zaywtdwj.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gt2whrqrawk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2evitvxtu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2wjkwzlgl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2idqimpit.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2lsxbwjye.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2xputfckz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gt2xoagsqqn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2kuwmnjpd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gt2eofdnjeu.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gt2xzubtkls.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gt2hffdamru.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubbtgnwg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdqlqygb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2ddkwafyh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2rsakdgtu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2ofwxhvce.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2qnojfoge.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2ggtwvgss.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gt2pymazcmn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2hrwtwjka.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2rwtagttp.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhsxczhy.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2kwprrtdb.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2kedebphe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gt2jxdpsfxe.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2ywsekohn.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gt2sxakluzr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2hxgvorok.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2urrtpmuk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2uuctxctb.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2whpjawuk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gt2ivcmuttx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puairito.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2diayyljs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftxhbrgz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gt2dntpyduj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gt2shcvvnum.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gt2shkrwgly.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2smwqbzrw.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gt2yvsylool.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2jwpwulzl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gt2xujckqty.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2jhhxjayx.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2leeqerki.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2nebgbaza.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gt2angblrcs.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2tewlvcja.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gt2qeykdnnz.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2xefnnlee.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gt2kigdjkyl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2cfvrzzvx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2wbscdmoi.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2cyyxfktm.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2spxauinl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2ntzcbpcp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gt2sxxdnegq.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gt2vvatknju.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gt2wigilcys.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2rtcylydk.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gt2rxxdeayk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2pirpppat.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2pclysgfa.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2jshsleaq.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gt2iarfonxi.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2lbyuwulh.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2tbkwkvqq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gt2dwwqnrus.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2qgvbcgac.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gt2lggqyoua.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2pegzsncb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2gxhfiphq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2xhbnjxvw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykcntvhi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgwzkxrt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2jojelbro.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gt2wcnxzldl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwqevxug.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gt2lvnfobds.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2dexswcqc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2fmcidbhd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2ojlgldey.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqvoqkyu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2jlqtqkyg.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2nttclptp.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gt2rdnkpzey.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gt2tkrmfrey.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2ohzrqyxn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gt2tgesarkn.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gt2ledeesau.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gt2cqasqwvf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gt2zdgxbuhr.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gt2niczvdlx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gt2coxrjacg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pzszuuyv.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gt2xtkhyrat.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gt2pnndubyx.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2xwaxuucm.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2azpjmmir.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2mpdwqphh.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmjkwbrg.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2zobqfkmn.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2jbsfsoru.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gt2ertupuuk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mydwtghx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2xlwtbmgi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2jhmxxreh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2auogbynq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2dyypjsht.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gt2wueznhbu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2cbelegyu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2xrijldiw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xupesaci.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2kcwelncd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2nilrndtg.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2qcfqcsql.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2tcywggaj.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2yoxfjzto.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2ahjsmqbx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2eojanmwd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gt2rexmokah.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2mwwsrbvy.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2wiccshti.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2qalrvfze.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2affwjith.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2blmaxrgc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gt2sryzsxki.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2wthfbbzu.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2qjfcbhuq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2xalfojty.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gt2nqcjqkcc.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2oalcqjpe.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gt2gcgdajyv.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2xxhelmmk.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gt2oxlvfxwm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gt2ywhcwxex.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2aywjrceg.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2dgpbppfa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gt2rvdqulen.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gt2gsmxlgci.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gt2sjizpqkh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gt2ezeuoyhc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2nvkgpfot.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2sdtkdafu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2hzfafoid.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gt2nysjghra.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2lnigphyv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2wzbyelht.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gt2qrvcmbkq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eywxxmra.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2oiqwnypv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqodhipx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ioyellap.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2emxylxro.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gt2rznvyftv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gt2mmhpkmec.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umrpvfxu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2kixlclwi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2frrfzrqp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2umuipeyw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2ifpyotdo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gt2ouvkhcoy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gt2setzraah.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2kueqrawr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2lhspwfjr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gt2yqbkytun.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2zdlvucgj.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gt2pzhotsvs.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2giwvszxv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2hgtzwtpr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2owxgtafs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2akrywgif.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gt2oncyoxid.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gt2jgivcxnw.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2uizfeadc.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gt2gltcyxiu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gt2wneofbvz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gt2ubpjkvkd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2vuvvkycf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2oyvdymqp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gt2nnbpoqag.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2tysvxvyc.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2uphmsuys.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gt2fhgvtscp.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gt2nhuesrew.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gt2tyqiiwye.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gt2ilzfogwe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2yihfxxsx.html


<!-- 参考信息 -->