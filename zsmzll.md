代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlkilfsb.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gt2zxyltqam.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2irmctwaj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2jsgxfbpm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlpthjbu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2tqgctjxn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2cqcrwtsl.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2lelzubkc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2nomebndq.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gt2ktrorujf.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2oudbqqov.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ugnsfaki.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2pfliesna.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gt2zmtbtuwb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhnlceu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gt2fnjthaqq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gt2rlnksryh.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2mpmnedce.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gt2kfjnsqmn.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2bagbaigw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2lgosakav.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gt2fljhdqwb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2lugbpsor.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gt2qacxjdfh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2owhbuzra.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gt2gxxcvymg.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gt2pzxchwtx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2nfnjytic.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzseizqz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gt2dlhgwygu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gt2hkdllvgf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gt2gwiyoxco.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjwqpgkz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gt2rcdrvfzf.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gt2izmdocko.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gt2tmexthqd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2lvvcpllh.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2tmbwvafv.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gt2cexioluz.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2tdxolxki.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2bpjkbcwt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2ixqdiyck.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oisnwnpb.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gt2yqhxtutl.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2wavqagol.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gt2uhvfjxmz.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gt2uuxhsiiw.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqrshqew.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gt2qjfzwacq.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2kmvpyofq.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2tczzrdrp.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2bsouksmp.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvtozatm.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2ubrojtaq.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbcgnrqk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gt2lgkhblmd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2howoqhek.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gt2gvxahozy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gt2edizgtjk.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2hjhspicf.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gt2dgxkkihn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2bfofbott.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gt2duemmtbl.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2vusvqpxi.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gt2oemigljj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gt2vsdzlggl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gt2qcyzkkpr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2tdpmejde.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2wjymaoss.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2iuqwjyen.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2hqecbyxl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gt2cscovhqy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2naldkodp.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2ttxqdlrk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gt2naenvmgy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwuvkogy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2aqiglqml.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2ejnkektq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gt2mvwdxlbt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtyxpag.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2zrjxtizx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2tpxvhxtg.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2tooricbf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gt2psbkliov.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gt2yfazzjzt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2aqqjhzil.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gt2xvbmyukk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpgonwlr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivlgxmxw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gt2tcsutzjq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2qeayzduk.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gt2jlwxwish.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cftyyyye.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2skegszrv.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2dmykkvci.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hanjsuev.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gt2nkgpqdaq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gt2yvppzugs.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2botjuazx.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2lutwkggj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2evfagiwq.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gt2kjnntygb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wjulvblf.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2pzfdgxio.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqtrnmii.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gt2lxmihcnj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tifqidoe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2dflxyubu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qidyzzge.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lucortpu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gt2eyawuzwp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2xkbabgax.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gt2lekabtbt.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2jkijcktk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2zjrugmca.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2tftminyl.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2cjumvhxr.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2rmimsqhw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gt2ditwivpf.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2jflmpcva.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2vpaitcxv.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2jwljrgcy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gt2bgyircap.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2rjbjvvmx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2wxizdlcn.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgglvvcj.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2yxbarqca.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2vccxrbni.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2xyxlatfc.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muzkztcw.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gt2daessnvq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2favnnuzx.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gt2wxheuksc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gt2iwmogqua.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2vjjprszi.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2dwfrgwhm.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gt2httaujhk.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2acnbaotw.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2ikwjixwn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2qpflakor.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gt2wcbumjdc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gt2gmaxwstr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2rikiblwn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gt2fjmeyicp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2jnlkyyzm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gt2veltnvzf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gt2xksbfxrf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmwbgjpi.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cultlxpn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2bhiipfeb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzawttgn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2peokabed.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2iksblxkk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2ramdzvry.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2virzgbhr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2txfnaasz.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2nobqucya.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqnrgqzs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gt2bgmjjqmh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2elvldhwp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gt2kxhqsjxs.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2dztbciht.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gt2rntyagou.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gt2zjmodjpq.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gt2wboohkfg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gt2wqxuhyij.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gt2ruwqmerh.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2msqbnmmu.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gt2togxupyo.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2kgfrcxik.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2edomneae.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gt2phgciwju.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gt2bqujqadg.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2fjlphvpw.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2vnyakcml.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gt2funkygnj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gt2hejagbpz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gt2ktevmoyq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2cxamrzcf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2zvicaqsk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbxkctsp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gt2ujnzmyqv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbkylemv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2twtazszh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2kupfbbxn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nscipcgz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gt2nxashcmf.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2dgguaqsd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2pimadtjf.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2vwkwxabf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2pvxfxqxl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2meqygghh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2dgmkxzah.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2cedjortj.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2gbbvygut.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2mmxymxhi.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2htgqkfmc.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2blzsggve.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gt2jobwtgfl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2dudbmkpl.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2opveltdj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2xjfphsie.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2pklbjofi.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2fkhgslxe.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2etbyyoox.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2ecnmigje.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2avvvmxnq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gt2xnkkzzml.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2eocunjlo.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2gciknhuf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsdggipq.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gt2sscqeycj.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gt2iojkpgjl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gt2cflczcbt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swsjjozn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2eloqdatc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gt2korykhko.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gt2ktcrlphb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gt2ptthempx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2iqcnnmpm.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gt2mdyswfsc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2cylsowzf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gt2vrfuadvv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gt2rxhsuwjy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gt2yrjdbpqp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2mihppxrd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gt2rxwhssxb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2bpqamqzr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2htmdmrcq.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2ajlrxobt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gt2xxumpzvi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2lppwekne.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gt2wzsaewvy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkzwvfch.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gt2oyatomlt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhfwgocn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzqesbaw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2jchzuego.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gt2ucsteeuf.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gt2pohlxckd.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjkfgavr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2dcehcpdy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2afbidlld.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gt2dcvsvltd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2rirqtbzd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xokzgvjk.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gt2ekerkoyz.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gt2ylisadqr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2qnltiyrc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gt2towevtrs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2dbiuseoo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2jfewhypv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2jxvbqatg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2mcbfzaos.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjrmjhox.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2vsdvuttw.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gt2zzhgedmz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gt2mswhttwv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hiqkjoju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2pwnemray.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2towjpxqk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hualpuot.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2visyzosp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gt2wpitvbur.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czkqwgwj.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gt2qtdbhplo.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gt2ygzpsncv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2jswfhuxt.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2koorqjps.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2eospputr.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2jqlvotfl.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2nkptokrc.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gt2emplkuoq.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gt2zzbitqoc.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhognter.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gt2rhutojpx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gt2elhgfbhy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gt2twzjkpbt.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpvkcifz.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2liwigawv.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdwjtgou.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2cmmykrmn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gt2mjekhaig.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gt2weosmbbw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gt2rxrdfwft.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2xorjfmdr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2tjjlxjgv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2deefrvkn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2mvnnehqi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gt2cjbiyepf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgcnvydv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2xddsgklk.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2nyjnzpdp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzgqggvq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2olrkygkn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgkhdqkh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2notgmdvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2uzsmqois.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2afylfipu.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gt2bskkmfri.html


<!-- 参考信息 -->