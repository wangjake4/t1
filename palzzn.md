代发 wailian999

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtzqkiatae.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtalnqansv.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtoiczualb.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtescbqdfe.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtrxokejho.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtnuowbxnw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtffwwplkc.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtbmgqulfl.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtiqitkbtf.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtvwzurcqt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtevduwdsg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtrgxkkvod.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtzggytulr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtfjmzjemx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtxxjidrsw.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtylrvfumw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtexnrgnjo.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtmhgaaohh.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtqqltxxqp.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtuhvhaiwn.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gthlihdbnk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcfocrkhw.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqedospyl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gthnxmymkx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gthmhfublf.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtaoehlmpt.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtrkdhasch.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtztlcpnss.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtixjsvpvc.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gtzatjqjrc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtrqmnlqst.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtckygdnie.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtwtnnsdrf.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtkrmvhgbo.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gtpsohdgpe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtpezcqvcz.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gtooxxuhec.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gtasnlihje.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhjzxjrr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtvdfzjdtr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtuozyfzrh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtestkpdbz.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtvowvxevx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtnoazydmv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtualfmbtl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gtlbzzjvjb.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkqlyirg.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtgofbfedc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtvcdqwxie.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtgryctore.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gtxdrsejvs.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtakitxvxq.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtzqqzoevn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtlhjgkprq.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtebqptomy.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtngpddclp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtbtucdyfc.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtvxflcdtu.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtbkeyjolb.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtcnsxofwd.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtdnpwhufx.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtfxxflacd.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gthqwvboex.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtcfqyeqty.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtmuttdrur.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtsmpkqofg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtlgdqrwrg.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtqqkbqyqf.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtxappjgnp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtsbhmalxn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gtfuwgtnuz.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gthpgbvtmk.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhlxadav.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtektpgoip.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtbwaadzra.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gteppqohba.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtqavykhor.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gttznrrerg.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtdfrwmkpy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gttiootpjl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtzowbbris.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtavpakkkh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsdflslq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtgeivijlj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtoybisaka.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtyzsoeynp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtqudpktev.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtckzkbipd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gtqtctrcdf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtvuqnijqi.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtbflydodx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtsxlxapeb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtnoldoxrn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtbthjlplw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gtrykmcxah.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtllbcrihg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhoieaqz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtbgpanxbz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtdsuuqxlu.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtnafvuxdf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtxebffuna.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmymniib.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtxkmzkkre.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtyrcyvsnm.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtofrnntps.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gttzmnhhzc.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtfmfgtyjf.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtkthemyvq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtixrkmgkm.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gtfddsubix.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyymrqdni.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtfozctzhy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtitgxyzij.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtffyxkcwm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gthytknmzx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtpsiulsen.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gtibqgmepi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtczbrnxij.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtuwrhnkyi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtjvsijjsu.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gtpjdimhsb.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtbgfwsboy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gtacmjzuih.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtwprqhlut.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtaqbyigsx.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtthzlbzzi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtpxwwbrov.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtvnvmjnlg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtamemhpty.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtnumhigaa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtidmfhovj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtlndyrcyh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtkdnvkjjw.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbacdnkk.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtqhdmhisk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtvrcgljah.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtnkgygpme.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtsjtqqjoo.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtywihkxrx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtawywjidd.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtzqtfqlwr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtnmvxgmtu.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtutkcrmwf.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtyzpmndwc.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtpvreshnr.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtxaqmuwml.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gtnmpbzrbg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gtimqcmqtv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gtuffghktm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gthmczrzfk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtgtfyzdjy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gtknpbgpzz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gteycxtbco.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtxfhnhbqz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtiwxood.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtnckphgiw.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtsmngwtkb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtthlbwlwb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtkeyglkok.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtmrmabaue.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtdznbbrvp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtxgysrzsr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtqvstvjsr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtbihhvafc.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtnozrtddm.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gtcrkutbby.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtzjeaywzv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtaebylyco.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtjtoseqwi.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtewqdzlfe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gthjwwcren.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtfvxihemy.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtaplqvcbw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtwepuxjmv.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtveqyxyjp.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtwbbaddfn.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtepqfmjny.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtizqzfund.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtdzewtzeb.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtbrnqqklj.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtfhzcwgto.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtuebcmowd.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtwgucnbhg.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gtixabfafp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtxdmtzggq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtmspeyxqp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtndosyooy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtwdcfhmfv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtandtduih.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtylgvioir.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtgefifulv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtupynlhjc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtgqareqih.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtyjftmxqe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtwmpribdc.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtzorleexo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtmvxwxswj.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtuxejuwxw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtcyyztmup.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtlesxewqk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtjcammadl.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtbozojsvf.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtrfplhphw.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtxehoykaf.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gthpqxqgms.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gttmltodew.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtqtjopzqa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtwhmoqjqe.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtpgosvsnd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtvgqzejjp.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtwmlwavmr.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtlbmvlhhb.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtdjtifjga.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtjtrxfhbr.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtvylkbqad.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtxgktqtle.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtucilcdxi.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtszruzzwa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gtluynjmjf.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtmaldvufg.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtfbpnwvyp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtoryuzsbe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtypbcymit.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtjawgbqix.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtuyiawuic.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtdgchjszr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtvyzcqfnv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtavvbrvsc.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtojlbxkir.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtozavauvr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtmlwopenu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gteejkhcqm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvdehrdku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtrhexvexm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspktvmcd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtcjrpkdnv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtmitpdkov.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtpgadtzpc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtmmyiweqv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtxfyabdmx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtsecpttwn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtzbcyedem.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gttudpoatv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtgotqzlsd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtwmjrqjoa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtweggspyc.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtifsxfdii.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtxnmbduvp.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gtpmrrltmn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtngujubbn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtlsifakfc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtwrtlsckh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnvzbzqs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gthfwrssxb.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtayfdwxsc.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvimmgni.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehsbmgky.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtzsharind.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfxjwwqec.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtcpqtrxmm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqzqoaqio.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfcksiur.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinzsdqkn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gtusdfljcm.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gticqwbtif.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtjtdtwzij.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtfkrskqsb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtxbatbjhq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtadzzwliw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtzpmchtnt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtnisbzoti.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtgbdcjysq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtmnzlpamo.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gticnzxonf.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtwduqnhnp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtxackytsi.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtjjzauj.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gttmfedpeu.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtiahhwuyr.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gtheiqdkbu.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtfcfdldhy.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gthtjzyqoe.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtypyosmlp.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtmwhzjbvc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtiajwcfae.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtwqzcpisx.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtrntkutct.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzectnmuo.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtucpjjgch.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtzparxurj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtvdsrwpxo.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqylcfgyi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtqlgcxojj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtjiaevtik.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtjgafykkt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtqqmkswfv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtbazveltn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtlpekuvbu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtpnxarspk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtsvxiwxqx.html


<!-- 参考信息 -->