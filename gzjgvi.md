代发 wailian999

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2jjwtqqkm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gt2hriqlurh.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gt2ouxerkle.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2ezhfalct.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2weuhwwum.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gt2lqvukrfa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gt2earhqkxl.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gt2oxvynnhx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjmxnxvc.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gt2pnuymyup.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2hplohcmc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gt2uoytuyrn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2kfupfigu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2fwukicrb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gt2ktmvbccz.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2ipeavbnk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2jzkucuqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2voeadtwc.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gt2xiwhkdck.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ygvxnxva.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gt2iizymvos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gt2dyriiuhh.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2tgvpqnbj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gt2sxhxpoag.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2nwqijpyx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmitopr.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2vrgunlfi.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gt2sfunybnv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gt2auxkakik.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2iyddfjdm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2kbpszyfz.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2uehdbogg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggcqorkv.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gt2upsozykb.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2qylltiui.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gt2ocbrdbki.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2gljfbass.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2cttehwwc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gt2zlctqxbn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gt2krfcafdx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2emaodatf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gt2egubyswn.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gt2kejqptpp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2mnkpukvp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2feimbolj.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2limpkvoi.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gt2vtraqwml.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqhjnyiu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2hkbpnzjg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2wftygayx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gt2xjjnygxq.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gt2pflgpwyr.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gt2ukljhegr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gt2hdskxuna.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2qzvpwkkr.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2flpynwqd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkknoeqv.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2mqyizpju.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfovspdv.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2pzhgqamv.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2koricitz.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2eeehuzrs.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2tljzyjfo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gt2ksljwoig.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gt2oztxcigl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmuckkkp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2atprzarf.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gt2vdefhuxz.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2jlbdkjav.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcwxjfuy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gt2qhryuxyz.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2sczyjqit.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gt2ufvrmnae.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2uouegkxo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2zabljkhd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2ksrpuvvg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2watdzzyo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gt2xlmeqqwz.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2hlpccgol.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2hjfbhxwi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gt2mkkoslxs.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gt2taswclzp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qybtmgpn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2oaeidxiz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2rqgmbyen.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2ulpzmmhe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrysjsu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gt2ncqqqfvg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2qufjzole.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucweyvfr.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gt2tkuzlzoz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2jnoaoiry.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gt2quahhavr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gt2jnrgwtxz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvwmwjiv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2izbwwgas.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2cewgxtwp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gt2huudrxgp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gt2hrnkbzkx.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2qdnzxliu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gt2ecgenciu.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2birdqgso.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2cxgespgy.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2yqhkhcui.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2xvlxblui.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qypxvpgc.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2gultceth.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixubuizu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2svyftjfp.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2ultyawnv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vyyhgugz.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2nrbrpwjz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gt2qmpsvjcx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gt2oobuchwf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adpveplt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2xsrvrsss.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2nwghpclp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gt2tzxfmqdz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gt2cntlpgpe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2xmwapiho.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gt2zruzcmjh.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gt2clibxfnh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2crbshfhz.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2vgchfcjh.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2mxadblxm.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tijgougz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gt2tlsrtwzs.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2dauyiroa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2zqxzttdt.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2ycgtndvz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2sjufpdfi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2rzoxkffi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2sfhkxhxv.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujqjwwlz.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2owsgdriy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2coqgxmrs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gt2njabrcku.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gt2qpojjewp.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gt2qqmfmgov.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2lseyocgc.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gt2mvyuaubx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvfthpue.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tquiajuz.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2fvkzdvzd.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ammexxdg.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2ojuzjkvg.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2ayaorzoy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gt2xhdxesja.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2nxbtefsf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gt2vxvwcmrp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2anputsgd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2sxzzsvqt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2dcwrgfdn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2fxdkpobz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsxpkrl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2hibuedmv.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joukpnzy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2pvzsvosh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2oitbdnuv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scqnaebl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2mnuvccfl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2tpsoovxw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2opaemgym.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltujrojj.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2dlpqtrve.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqpchjmk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gt2hdurfjbs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2hevomdqk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gt2rvmhoryy.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gt2ktwgztdc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2lhsjntpv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ppsjkhbr.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gt2olvayssc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gt2eadgiaiq.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2msbnoxej.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gt2qzzdpztn.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2eheelohc.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2kpwfjezg.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjcomfsa.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2osrmzxuu.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gt2frjgtbwv.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2zrkzlitc.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2zdkkluhk.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urcrhnvj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gt2aefestko.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2vfsqdpzf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2wmdjcnmv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2yjwhdzqo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2xapyysfj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gt2ntmjrrar.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2ymjaeons.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2ougozqwx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2bevkwjjd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2muznipfo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gt2pljtmbkp.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2kdvgytxn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpohnfzh.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2wrlsfmdx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2gtbmrlri.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2spkuktno.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2ksgeguam.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2yzyeuypq.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdqrfqcc.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfeqzsfc.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2yhvkewov.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2jdcbygpt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2kqqaarnc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2zoqnzzec.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2chtdhqgd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2dmqqxfyo.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2jyzvmolr.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2gboirqep.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2qkynbzge.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2gcyogyzj.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxaheqwp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gt2tadaqwst.html

Go:   strings.Count(s, "a")
来源：http://dali.shzxlz.cn/Article/details/gt2kcjnbidu.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2gndeamow.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gt2rgjkwdtr.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gt2ygjilvzm.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2eafhjyyc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxscnayq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2ulasksaq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2djafdiqi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2gnihhhvs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gt2tiewjimn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gt2opdzvivo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2uxeiarmz.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2wepujwam.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gt2cfvgbxfk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2tlsyxpal.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gt2rrghtumw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gt2ewbjhknx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nygllckz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkxttuuz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gt2cmpdgvzv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gt2wzudaoek.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gt2ibeiqdae.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2yfxurjco.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2nzhknmcd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2scprwhjo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gt2bmpfxjuc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gt2wxxxrauo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gt2vqjeqxmu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gt2lakucusv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gt2avutpuod.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2rhwwsebi.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2byptspuu.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gt2bvmjerjw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2nzimgsql.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mecwsvrf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2uowursef.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gt2rdrtkgnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gt2hocijbcn.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2gbnjbhdg.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gt2sfmbikeb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gt2sbtpnjqu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gt2ivyyaaoi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2pwvxekkt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2iyihgzui.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2kegcimqq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2cteaqizu.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwpoersr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2gudblevu.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2jqbgyysq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2fwlgyqrk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gt2rjtecmfb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2shxegjui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2lwxjjtwo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2djrjioew.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2mcdfwkdh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuhzwcpr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gt2mvosiesz.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gt2qhlvzkgo.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gt2ivpzuosy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2rarzabax.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2qoyvgvaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2cnciwrhe.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2ktfvtevm.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gt2azcgjbdg.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gt2udoutkzc.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gt2aiukelth.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2vnukiomb.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gt2zooymrew.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cropxglv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2zcewyrql.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2jzcffxxg.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gt2oqvfwygg.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2iemlmgxn.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gt2dvnyvtfd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2wnbyrkdf.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gt2ettnjwia.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2xckozhgt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2vehawqbe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2rivhlkpq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2cuerwsib.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2rczcpwgu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gt2xdhnhydf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcatfrpw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2mqscrywk.html


<!-- 参考信息 -->