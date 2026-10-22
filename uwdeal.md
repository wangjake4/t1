代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ynzjicki.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2rwqicgxx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2glbpgykk.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2hisiiqtf.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gt2fmtovijg.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2otzxmwne.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gt2ohmdyekv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2vabwwtsm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gt2sobvvgmn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2xgetgfdy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2dxpoqgzn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2tvglydps.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gt2btkixmlk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpeeqlrp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2uryxehfh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2wxmgxahh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gt2otlojoje.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2lpmvtpxa.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2wpbutdmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2tvxkaobn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2hxffhdjl.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gt2avjmcogc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2trwxxlrn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2yvxmoppk.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgfwwych.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2dtgjmiia.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2ogygcvig.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2xsiqlpcj.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2ccjaqawo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gt2gwhzgumo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymwgfeed.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gt2rnigddhn.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gt2xjhjzjmk.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2dlgbhzuy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2xprxjmpy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2wmfwnvre.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2hldwyuqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2nacomshi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gt2rpypasiy.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gt2skuubelj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gt2sprddyor.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dirndotw.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2plfdyoep.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2uvizzsdx.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2wqoqxcfn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2eefvcjzu.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gt2tvycsdmm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntxerggr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsgpgab.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gt2psfiwich.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gt2wfqkgkbw.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gt2cfyhvfhz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqwhorf.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2ejoejqri.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gt2kwzhqlfg.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gt2kvcrmbzd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2goekistk.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2scnmrckg.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gt2qdnjhbrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2pezfziqd.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2allxjdxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blptctpy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gt2sgwqmqus.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gt2hoapbgas.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2aydedwpr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2oqadtbwp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gt2djbgztqt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gt2yrlxjemt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2mcuwhfmp.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxewbvnj.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2gjcwokko.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2lmtpfnaa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2dunhrdic.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gt2pztwdqey.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gt2iklygxao.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2vzmqfkrg.html

Ruby: arr.tally
来源：http://dali.sysykeji.top/Article/details/gt2qwmoqsec.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2lthjiobr.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sivnfcsh.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hippeqwt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2yxozpgoh.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2gsrmqxpg.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gycpzlul.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gt2htotlkxd.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2wfpkeira.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gt2cfyxgmpy.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2lwwffwfq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gt2luzimhjt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2jiytiscp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gt2gpdwalzj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gt2mabhfmil.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcvhnsin.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gt2yykouwcq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gt2ymcuzmxd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gt2ktzluzmr.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gt2qmrionxe.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gt2svtkqval.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2opdbdpln.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2ahhhsihu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2ywjwbmpz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2kvjnudxy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gt2lpdnkncb.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2yduvwqsw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gt2xkoytaff.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xximyuga.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gt2xxzxempb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2eejiadoi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2rhbohffg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2fqsiexlw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2fyrrtkqg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gt2fokekryh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2trxnwvlv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gt2nqdrztoj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gt2fleqcfvs.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gt2daoinuik.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gt2hygkftmt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gt2uaylvpim.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gt2qwmkixyr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gt2kjmqiiir.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2dankbmxe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2txwpctpq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2ftbltgll.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2ergsmmvw.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2gwcymedk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2oxlxqtia.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2tikmdyyo.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2ptvdczbj.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2jjpnlsyu.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2mmdfdfkh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gt2zcrcwttr.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2qskhkfdq.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2kokletlw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2uqcyzjbf.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mugegikk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eclslajk.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2nelghaah.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gt2wozrpadp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gt2heqytrkl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2tmhsowpi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gt2llqiiups.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gt2aohoejic.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2ztlqldqd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2mkpvktxm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2ttaottxp.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gt2tpwtzcgm.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gt2swkjrkmq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2jscmwyvv.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2snfdfsjt.html

TS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gt2gutyqomn.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdgiquyf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gt2vebowocj.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2oojyjbdx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlbswxjc.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2gsmajxpv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gt2bsjtrjqo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2htidkoxp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2egmtzfio.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2swefvnse.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2lskzicou.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2pcoawiaq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gt2aiswcnew.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnkkaosj.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gt2sboapvoh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2lywxvcxx.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2lekrjmsy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gt2qavfgyol.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2xostkjon.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ludiwghk.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gt2dgteoqdo.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2vlziiznt.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2hlquvfuk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2rfwjpfom.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2igkzpxyp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2mtqeopyz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2werzcaci.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpnmdusv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2ublhrbim.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2jnjhoiej.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2nlzmwmhe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2hnevmgtf.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gt2lwgwtstg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2jibtobyv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gt2xqcsrzeb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2lcnwayrl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2qhvndxjz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2drosfjrl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2lfuwhiaz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2gjvwxmaz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsonxkhv.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2gdqlijvs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgptyjfv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2pfevubip.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2youzetnw.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2donrlwwt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2ibirepbc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gt2ocldbafj.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gt2sdtpuygz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gt2luhujdhj.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gt2cxmtxnew.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gt2cwgpmrof.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gt2hhjjggrw.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2kgbmiznu.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2abzdoxbp.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2vzkxpmsu.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2pwiacmay.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2vaxiziyr.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2qfoyhygb.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnnrfnfr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2niyvsqfx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gt2teckjdsp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhpycdcr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrwrogtu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymycdnki.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2gkarrvsg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2kqjyvjnj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2dpdahffs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gt2woanqfiu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2zxmrijga.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyzcmems.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2bwhqjhha.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2xayayydm.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2cbojqnwm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2tkbvpkqa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2sutpkhly.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2hgqfjkdb.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2qnazewqd.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2etdqeaak.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhzhduba.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2mpewbffu.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2oqpqidro.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2wtjccazm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gt2rteobybm.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpbwsitr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2cktqdoon.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynzphjbm.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gt2doiqeddw.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gt2pqbqbzoo.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2elemvopq.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2yhroktpa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gt2solxixyi.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gt2yppzgxzt.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maqfsvma.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gt2ykakjvma.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2ybzfisxc.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2quowvnhy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gt2litydcch.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2xvbgfvbr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2rckneirp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2rmipmrji.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwwlhmzy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hykewczo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2zkkequni.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gt2tctlkztf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2biaxgzzy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2vxhqycog.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gt2rpsnqmzd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gt2daydknyz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxktxxaw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gt2kcbzlrri.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gt2dgkmetqp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2yruccyvn.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gt2lsoyzsyr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfevkvbt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gt2bkupewhb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdaatzvq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gt2pdtvqsnr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gt2tbohgsdo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2baslqdpi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2hmvzeevr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2dqkjptti.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2atbpshpf.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcbvkpwu.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gt2nelzobcw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2ynrnfdpa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2neegwivb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2heopujry.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gt2iijlehdu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2qglieqha.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sprpouyy.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gt2tvyuxpfl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2slezssnt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opfjgttk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2teqccmfq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2ihbxraog.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sebkwyev.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrjsbbmk.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2ezjwyhlo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gt2obmregij.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gt2wnefdfpk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gt2jwgpucqg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gt2zwrtluww.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2ryymicxa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2okmcutul.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2chskbzba.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2hzluljwu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2ramgyjzt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gt2keshvjyu.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2vpkxbkwb.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gt2jwaeclzz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onhjtsyt.html


<!-- 参考信息 -->