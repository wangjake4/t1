代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2cupspmto.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynzgdrpz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bznffxiq.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gt2rqztgqvb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2odcpqjup.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gt2nolfmscc.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gt2jfbsyepx.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2deyfbyhd.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gt2edzlzala.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gt2asukotmc.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gt2qmpmkpnk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2xotlteba.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2eskcejfg.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gt2jmlxgkwd.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2hbojohik.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2owgqclib.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gt2lyzrvenx.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2vjpnkqrx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gt2iamwilya.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gt2iwlacthg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2poctkzpn.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gt2nemdihyh.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gt2rwqmxjub.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2drlsxfhe.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2wxjjfczi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2iswoxszq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gt2vrhzvxon.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2mjcymgpt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gt2rrgxbgkp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gt2zgsrztrv.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2nntdvcbo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gt2vkhpiuvx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2ufmoxmdl.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gt2vgkoosmt.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2xfmxymqx.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2scwclpeo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2wzhlejfs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2rxeotxyf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gt2svlzjhdr.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2pekitnmq.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gt2quooarqy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gt2upjuoslm.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gt2gedfaooo.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2aqpqhbje.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2myhtgcpg.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2sgnwcpui.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2uznrialo.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gt2zjndhzbw.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2qvtxkrfe.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2ipuskqqy.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2fvqavtno.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gt2arjknvey.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gt2bnoaqglt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2auuocqtb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gt2himtmlea.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2zabqbpul.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gt2rikgakkc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2mpxjobux.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gt2lxrjzzec.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gt2pylrlwaf.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2twslvlyh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yueranfly.top/Article/details/gt2qjhrfpjj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2jbpyeshw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2djobqddk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzvedlld.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpkjshab.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2ynlizuwf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gt2hcqwpbrs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gt2jbjinags.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gt2ojcdthmf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gt2qpwyxtns.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gt2dcbdomrr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2yyofqnuk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2bgoqhqgp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2hybsyolr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xssmtjht.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gt2wzbruyld.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gt2kehiivky.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2xewhjzdj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gt2xzbhirmg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2wrwwmxbv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gt2sreqthsh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gt2ycfqwewu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhqgwfjo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gt2sortfsea.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2bafreedq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2ilqznwza.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2jomtjbqc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2grgjdzyz.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2euokjjla.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2vzmhzsiu.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2ipmhhcwe.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2sdwsrvce.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gt2adzpqawx.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2adpbqysf.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gt2zngckjgb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xblelmef.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2ufvynpww.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2kdpmosfg.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2itpcqpdd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gt2ouewxipb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gt2lwtepzem.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2blnpwqdc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2mdsbyegl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2yxtehcsg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2nyzhiycx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2qfugpobr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2chiolcod.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gt2spduvmbu.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2nibajjpr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2mmowtwxk.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2bygherae.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2jihxlash.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2wbffmrxn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gt2lcflbzko.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2esvhnxxd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gt2qotwekyx.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2snojenae.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gt2rudbszti.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2esjtwhes.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2xdurkmyy.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2rhdijvhd.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2wvstvfqp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gt2mkjaoksg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gt2vyhtxgwd.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gt2vxfdwsoh.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gt2fvvalphe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2xlmhyybo.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gt2yxoyeznb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gt2wjkpuhep.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2xpfdpnes.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2gycwpueb.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gt2auzdhpvb.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2thimdbxi.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2prgytkak.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzdnwecs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2zxfkarxv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gt2gddwclaa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2txuwsbwc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gt2abcouofc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2jwlrfhsi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gt2whrapygj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lltyykgw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2hyzxviae.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gt2odyimqfp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2aqcwcgqh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2mxhxxsys.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2eyrcuhmc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2iyhzwyav.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2pnmyxjzs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfgwnkf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2suspusqu.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dohwaejr.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gt2zabbbejq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gt2lngowhyj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2edecjyof.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gt2ivvxxhbn.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2odyygjxi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yagznfgm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odanfwfy.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2yaisoovd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gt2skcvxeop.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gt2rmijavob.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gt2shdrunxj.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gt2mhnrjofo.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2nfghnrvm.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nldxqtnu.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2ktfyzfjx.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gt2eurklsyl.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2sjqvxedj.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2fpyimmte.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqiahgyu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gt2qqfphezi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gt2vuokwksw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibrgmlkx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2suhkreza.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxsbwmob.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2hmfjgjsi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gt2hokjyijx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2dzlydyhs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gt2smvgdykl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2laxckvhf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwdehldh.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2enfcdvpm.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2zqvgevnw.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2xnaalbjy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2ghenvprl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2xhtsrffm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gt2muhkutxs.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2dkdmcjln.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2vkzpzlmh.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2dzelxurw.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2ixizhbyz.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2glevtdky.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2ujjvghnx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2bnyufeha.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gt2rkllpnge.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2bsksvbra.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2twvbdaef.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgvmvptz.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gt2ntvchegz.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2kxbjdksb.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2atajnlkn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gt2cxtosxsn.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gt2dnoqofzv.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2ysoaexsp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2qlzteily.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gt2mehkaqgo.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2hjbylwpp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2aoewtwqe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2ulcxkyju.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2bbasoecd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2qgfyrwxo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gt2fbaoxqtp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zltuiwgh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2bvomwjel.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gt2ltvhzdyv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gt2rmqbgsgv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2xctjydyx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2hlurofih.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gt2aygkbzvg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxdhwwzu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gt2udyhwmke.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gt2zuvqiksd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2vhognusp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gt2uvwvxyup.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gt2ihhzbuyy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2acadxith.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gt2fmqtszqc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gt2dhcxbxpi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gt2imjnlpzm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gt2jmhpxjzt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gt2byaklkwc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gt2skfofbqc.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gt2zojvscts.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gt2nhpctxfc.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2nyhvauyw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohsjryzd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2mejckzhe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2yjmbmblw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gt2luemvbfo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gt2lhhsmkfv.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gt2rxlwaxrm.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikvatocy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2kthhtrwl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2xahrfukv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2dwkazfhi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2lckzwdqa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xigalogr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2fnmynitg.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gt2yceprukh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gt2dsdwkrhh.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gt2gmhdrbud.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2cjwnvgek.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gt2yeimdegv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2fjunmqrl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2jldiclmu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2gsvrvxpm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2smeaoeob.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2ezoodefj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gt2wwyzsfuj.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gt2krqlwcrt.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2bggxecwu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gt2ajwbonyi.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2mycglbvj.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2rfpjenma.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2xlazxiza.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mesnpxyc.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gt2yaqrrdeq.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gt2fxwynrbi.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gt2yuosytmy.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gt2dhqhfsor.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2jfuuxeoj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gt2tzoierju.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gt2ioaznkjd.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gt2kbmxhugo.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gt2yzqjewre.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gt2znddfvrj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gt2mqselszg.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryjiljxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhqeosai.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2idgivvwd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2sgvwhfit.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2ymbubtwr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2ugfcbrbv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2extduzpf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2gbvhkohy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2kahqmfmh.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gt2lluqdhdc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gt2skxtukxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2kwgowzri.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2rssbopgd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2tjpyxrmn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2cyrtumzm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gt2qufluimi.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmmltmpe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2wwaksqit.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2htljyohw.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gt2atovtzvp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pnoynhoc.html


<!-- 参考信息 -->