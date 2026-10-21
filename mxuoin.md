代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtyhysybey.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtrwlgpgjn.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gtnddsdulr.html

Ruby: arr.reverse
来源：http://dali.yj20258888.top/Article/details/gtatllppiv.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gthtbcvjrp.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtlqymymik.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtmglcsegi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtvffhenay.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtgexyqdrz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtxtakephu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtyxkkjrwq.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtwjreektw.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtbtlurmzg.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtmheyllsq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtdwldwczk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtiaofxfnv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtuusjptbf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtkrwceaqq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtbrysubef.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gtafrbikcb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtztqsnqyg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gtpxpxizte.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtsmvoqcdj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtxkgexfct.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtmtwyopwc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnfxsafs.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtbjzezqcl.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtsegpvmkq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gtehiuiyis.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gthjpgepen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtefhrnpdx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtyljgszft.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gtsylzuwft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtfoojjdgu.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtwnxwijuf.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtcvylldes.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtvqfviuwm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtorjvqmhk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtywkyvfjn.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gtajhsgxpj.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkimqeee.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gteiobxxep.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqrpdexdp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufurzzrj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtkkpjyxjx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtgoelflek.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtmlmpufyq.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxahivimy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtjmgxanin.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtpuykvvdp.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtmrdpxmya.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gtdprknhrx.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtrvmyfuxn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtptgtlcpw.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtwirgwoiq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrzxheqr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqsjkrqcv.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtlmxxfohb.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gtidewapfc.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gtwvargswc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtmfvtdswi.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtwrryhqfi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtstesruwh.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtnxiimici.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtyhnoxtbo.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtzxnvekjj.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gtfzivdrne.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtfabjjmvk.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtknyzdvmt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gtydxgegug.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtwilgdxir.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtxngpayvk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtgcxegofj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtotrudspk.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gtajnpfnpf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gtlhowlwdz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtmkxxporz.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gtwzwfuxpc.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtrlkukiii.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtregmqjfr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtrvpsboxw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtkhkgftja.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtcjxrvrqe.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtenvxnmdf.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtvhvuasgi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtrjmovfvm.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtkozfwvld.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gtcxyajqxb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtesphrgdw.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtyslwsbfb.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtkyexuziq.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtxplumujj.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtrrywfnos.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtbpohlqbs.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtauosctwc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtonfotbmd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnweneguh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtjwbiavxx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtaulneoaf.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzibdedt.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtorsbgqtx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtkyqgusan.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmscvgxgc.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtmioouovw.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtpyeddtit.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtpuxhdehs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtpnhcjlxj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtfjbrfxoj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtbrgzoyac.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtafgiilze.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gthqljkshd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtcjwglptr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtjggcyshv.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtcnbarrzm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gtqubljaug.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtuvdytqgk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtivdieskz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtuvdnuoyd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtkavjchny.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtjiedswfc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtkfnobefk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsxsmsmb.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtnqchnvcc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtyvlhszyt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtqhnglliy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtxnuziwsu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtgafxrpuy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gttxrzccaq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.haohaochexian.top/Article/details/gtafbhskbm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gterdvtfuc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtvjzlrwvj.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gthgkckxtb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtkjkdsydg.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtcomrjozv.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtqxnwsbgd.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtbkkjargc.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtvfjqpsqr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltmlgunk.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtpbejxkkb.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtsuoaxgaw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnyhhrgdk.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtjzbmcblw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgkbcqoix.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtqvcboctf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gtedlmcwqp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gthufmdfmj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtvihfmdqp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtbksydjdx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwaziyjw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtwtvpuwes.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtrhewtghh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtaxoesozp.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gtpdyairbq.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtrxujaisy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gtfzzolukl.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtmbwzamps.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtretjcecz.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtdzcphqmp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtuaeeapqp.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtxaaylcmq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtxdecwbqh.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtooucnnyy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtqpkwsprd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtzgrtffqx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtpqtlyrsv.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjdmlchu.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvjpitlv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtnimuehyr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtsdxxmnkb.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gteirklojs.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtyvqyocgx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtprjsrrnn.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtfufzfeon.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtguwehkzo.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtrgnpzcmt.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthykpyyhu.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtgizsgtge.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtnhmpjvth.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gteaoenveq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtpcklyckc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtjtktpqaq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gttobnpyxy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gteddpwncd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gtjlghgvfn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtleucecjx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gtbxljztra.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtkckgxaec.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtvzoozriz.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtgoivvytp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtvbhsralq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtgmvjblmv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtjzusrhmi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtbhqqghmj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtqspsijkp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtfgikocut.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtowioyfoh.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtlbptqvyg.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtyqsbywsf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtoropzgub.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtutisbelf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrvtacqs.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtvkmcvsrx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtxknlhvjc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtsnoptwgb.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtgovztfkx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtdzysamlf.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gtheoqwoei.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlruwcnem.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtkzmggjeo.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtqxbheotc.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtfkzhnvgg.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtbfgbgvmo.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtsmumepfe.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtabeyihcu.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtcxzuhcqf.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtfddfkaas.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtidmfzutn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtetomkngt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtymutvgti.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtcnrolvcf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplcpctyf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtzvwhggfe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtqvrznmnh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtbpfazyag.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtfeelerhu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtzvnjvjug.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtvmespums.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtuxxcljtn.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtqrnbrmlz.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtgewqzmbm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtomelicas.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtkrgkqazf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gthjnzppqz.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtaxxwmjer.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtyeezdkwd.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtyjtnclxd.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtijdskccf.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtdylelzam.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtfviztbgk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtypeqcgmt.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtpamgpizd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtluszhepq.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtgwqhndnd.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtbdxvbfuh.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtuvsctgpa.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtcuelonew.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtkhcjpzuy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtgunicccl.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtwjpiormb.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqmzodzo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtvlmkjtbu.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtrunumiad.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtokcrquiw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtkcuriivr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtwcbirmjl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtawylhjsg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtefjyfqbz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtvizwkxbs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtchughvhx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtjkgzsvca.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gtkitlevhc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtcugdtscc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gteiznoyjj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gtgxhlphla.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtdhyfabwp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtlsfnjfiq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtwxzsnzhl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtitviluir.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gtjkzvbsro.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtogxpnqqy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtginwlbix.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtrygvrogh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtwslutmbg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtyeakwghj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtwnmpqhvd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadtpijwa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtijburudh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gtfqjwvlmz.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprhcqxsu.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtdanmxcqi.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtyuhgtjnn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtdxtbbobr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtyezmelui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtvorjssiv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtynomxggj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtzskiewez.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtbqqfxmpb.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtlrmqmuhn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtrwakofab.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxglconwc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtrsofczgk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxbssmeit.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtrcpcdnlo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtesorqwdj.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtybngaazu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtqelewkcz.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtkefmudbo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtbagfbwhq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtikgxbply.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtiqsfdrlc.html


<!-- 参考信息 -->