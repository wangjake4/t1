代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gt2scokioob.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gt2ognxioyh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gt2mnsbwboq.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gt2vxzgledj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gt2spqccnzt.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gt2mohneosd.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2nxzaakad.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2cfdezkpy.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gt2nizjdavs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahzbhmti.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gt2xmtzcawk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gt2xhcjmajb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2bgrgjcxp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gt2vspxfptu.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2vjhpyjzf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gt2awpcnjkh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gt2atvouknq.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gt2fvrhnxdk.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gt2bcxwwnwp.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2vojqebzw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gt2zuvrmoeb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2dxvuarof.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gt2lhfugzne.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2hevallgq.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gt2dvdkmmaa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gt2upfrqyyi.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2sercirzj.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2iolvwwmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gt2senlurcv.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbqnjuzu.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2zaawvsfi.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2zeoibzhd.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2tfkdxbqb.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gt2yebjothf.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tluvruhh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gt2esmnvxov.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uahsfqhi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2fdmgbuvh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gt2nlwacdgx.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxchsllc.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gt2ltzoervn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gt2dbguxchb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gt2cyeuosjd.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gt2ginkzwpn.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gt2vhwztssa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2svwizurp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2qljcflfk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gt2dnfpcbjp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2muxrccvr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2muaiviio.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2nrcpwqof.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spicpvmj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gt2axabiami.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gt2fbghdvkb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2knytwukw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gt2zyhgasco.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2qdsjpifh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2nczfmstq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gt2veuvvfmg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gt2gihfrbng.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gt2mrhpccud.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gt2ltixqwgu.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gt2mhrczpvf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2rlnrevgc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gt2stqsflqx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gt2fzcxsddn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gt2whbovimo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gfoftdjy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2nkupobrg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taabbggk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2xxdspmvv.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2sqxginpb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2cdaqozmc.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2mauqyovq.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2qzbwukmi.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2ctmllrai.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2odejkghb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmsbgkcx.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtqieqyh.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2vbawanwr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujpaibhd.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gt2nbjmktzn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2uwpcdysj.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhjeuiug.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gt2eocxycev.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gt2eqnmiztt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2bguzyfpk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2uedhutgw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gt2spywfupo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gt2pollslqr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gt2ywycvesv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvjxhbqp.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2qhwiyklj.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2aisteuan.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gt2jzchiqca.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2qtodfcqv.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wivbtovr.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2bspjxpcf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcouwiwr.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2burntrel.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gt2pjzfntxc.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hazbclci.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gt2nfnnhenp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2aruwthwe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2umnvqgxi.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2lpmajvyt.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2fkjizdkr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2abmtjayd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gt2qpfyseua.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gt2xrcojubg.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldkbekys.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2jbhiphxn.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gt2kvnjuyxg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gt2fdixpkwr.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2ritdmgch.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2ibvaelzi.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gt2oxoasali.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2kjjnllvl.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2sxtgwpxo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gt2rjquedtz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gt2hpjudlot.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gt2hevjdgfj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2vrzcpugf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gt2zyykqxni.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weqxnslm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gt2ejonypty.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gt2ikybxepr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2nkigbahq.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfftkcwk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2iaaqfbcv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gt2nvzkonvw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2cweqljzq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2aksgbiww.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2uqgleeng.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gt2mqugwiai.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeegkix.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2endljrcq.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2wktejqmt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gt2yftqgxue.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2jolsxxky.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2isogpkif.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2idsubttp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gt2typrykxb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ftpwsibe.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaystpy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gt2zudmnupp.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gt2olxgrbax.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmmjrgym.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gt2gwiqfslu.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2uubvvqjv.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2dyoolugp.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2leyhugff.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gt2pminnkxf.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2gtfpjhju.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fudkozlf.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gt2wmozyxrf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gt2iqwdyesg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gt2ywuoxbyn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2cjhgdtwz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2xkusoumt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2sikjlfqa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldmqrzte.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2oxjflvww.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gt2jwcclwxn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gt2keznxvnd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2bvdylmyz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gt2wkcqvsga.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2shsmabsa.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2grpmxpbo.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2xopvohoz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2obnhkowt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2fynuzbkz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gt2ejypngrd.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gt2okhuoduc.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbdsxvkd.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2kpyjjmit.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2inupphtb.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2bzxrihft.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2qajttldn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2wpobqsfd.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2gbdzxmzy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2flvxrhjg.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2xcexzlpa.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gt2gxqaxecb.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gt2zazzsaqz.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2tgkkjcrf.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aagmmawq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gt2qpmdlkqw.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gt2jlccqsxp.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2hoefsbfv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2herscyve.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gt2rbssrhsq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czazakoa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2krlezllq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2uwiemwgj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2xqtgpcoo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gt2nqeqpkch.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gt2dluvozso.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aebiypre.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2lvhhicby.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2gekclsho.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2mjgmmbic.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gt2tctzoiol.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gt2ivckxati.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2gflwvnff.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrusgryo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2hqciyemt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kodawvdc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2qvgmokpf.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gt2jhugvwww.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gt2mlkcyxpu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gt2ifrfezkc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbjfrzkn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elrjjzxx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gt2wghikwve.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gt2xdfagoyn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gt2wrrfgjhx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sagpntjm.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gt2louftqgc.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2xxdiltxq.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gt2fxcmnimv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhyllkuw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2bpunqfla.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gt2vbyqogxs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2qokmuxkl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gt2itxkdrqz.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gt2fleuprgc.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gt2nltuyrsb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gt2hfhqjfxg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzsjztqn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksmyreoz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2ipmafhvn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gt2aoxtslih.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2xvlcfqse.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2gkhkyeod.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gt2jcetzqhe.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2zsehaemy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gt2eitonzie.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qouekppq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2fqdqbhvq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2bjpnfzxb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2talbstwn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2hflrapuy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gt2bfzdqhle.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gt2positxbb.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gt2tafthoxq.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gt2otlcmdrb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2tqedbpyl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2anjjctmr.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2eewakrrp.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gt2ymqmxooi.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2qmoccriz.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gt2wwietymi.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gt2wzgiazha.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gt2eixovpvp.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gt2cdmdakww.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gt2inlzampq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2evhxkkyf.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tmknygtf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjcoyoqj.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gt2urnvrctm.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2vkqrwdag.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gobergav.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gt2qrqlxxaq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gt2rznvievr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kaqebwjl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2wlivuwfr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2pepofuxk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2johldoea.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gt2dhjhdxvs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2gscvwmzw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2zcusytxm.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsflhyyq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2udndjvpb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvxdczza.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2erqlrchl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gliktrrc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2edoyvura.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfzvzqvw.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2pcduukpc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2skblpzjl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2cjeahkae.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2gmwikuxm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2klfafccq.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gt2svlyfstk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gt2jvndoehw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2jtpaynbh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjbohnsf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwhiajgv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2hmkrrjwm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gt2gddgadyn.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2lgtxzqlr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2jlrcqgud.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzltckmg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2ykcvovbj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2hmkvmqxg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2hacjmcgb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2vptxsufs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2xemmdsdr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2obkfsgmf.html


<!-- 参考信息 -->