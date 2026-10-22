代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2purlrenl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2rwsqjiyd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gt2xywlahcf.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gt2gghzhhjx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gt2kizufttk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gt2neayyzdy.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2clymoqfk.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ifgpmffd.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2jaycshie.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2ojkbxcrt.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gt2xsumlvbb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gt2zkavaxur.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpqxqszb.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gt2sghqhjkp.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2hjlzkfqg.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gt2lkggrihi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2avmqioqe.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtqgjhsv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gt2uyzysqqh.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2aowvgcrq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2lwdtxjot.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gt2zsbkpfqh.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gt2yvuwkstu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2iwnysyfs.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gt2cqgpofcy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gt2gwjprhla.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gt2mveaezci.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2bcndwnfj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2fsrtyntg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2syjoqspt.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2fxzhbspy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gt2pfifduvv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2rnfdgrcc.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gt2yeahlscd.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gt2umnthpex.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhwamvrb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2gppejvpl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2nbirelxe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gt2skuxldva.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wonyvvtx.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gt2iwnrpize.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gt2ptopkvzk.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gt2gqfqnyle.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2mttsrmyr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2yxlrciap.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jushthun.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzkhpjkv.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2njkasjcm.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gt2jysadeou.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gt2lkumjrvl.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzzxocsb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2omuixaex.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2cpmvlrzk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gt2mhllsdtc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gt2jtxyoxvb.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gt2cnsmxarw.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gt2wvqwcjlk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2yytcewmk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuusawaz.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2nnadgstf.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2uctxxcrx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gt2eomzfksr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2bliabfia.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2boibwmmj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2bovcaohp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gt2mlgdpmyx.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzbfbaew.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gt2erfpgost.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wlptbdpe.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gt2lnztqwil.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2demztibr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gt2traugtzh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjoxiqen.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2gegqrszx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2iswbsxsp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gt2hhkiudtj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gt2mptaeaff.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gt2ilqjsnbj.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gt2gmibiqqa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gt2ickxceal.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gt2gcleizhp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2djrqlosb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gt2czonomfl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gt2msfxwvlg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2nkwoqeqq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ztuqaalu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2dfpncfjw.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gt2zcpigsqr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2cjehkdlx.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2irqbjhks.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2tnpgvifb.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2arleybrv.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gt2kmabqlmi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gt2iwihgigz.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2ssjhdscn.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2czxpsczx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xyrdtdvn.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gt2dbvzyuhd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2udyqanjn.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2kdohizrt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gt2kdgxkmxj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gt2uhgghwfg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2crtawoil.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2wplnrqqw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gt2renuxnqf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gt2ngyvscub.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2yipnzqbh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2rfpkhluc.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gt2qzobwgyg.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2pgtudoeh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gt2lirfaedu.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxegessc.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2fgobgolr.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2crvlyruo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qktxyhqr.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2ppnwzjcz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gt2tauzqjly.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2fzjpfgci.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gt2xdypktyh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2xyjpcyqq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2aphahnye.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2cyabowzz.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2pzpglpur.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2etzrasfh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gt2uhvvqidp.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wclzjnon.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gt2lioerwjj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2wegdxcql.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gt2kibulnqu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gt2pqwrxgug.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2khzdzerj.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2ginalkfr.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gt2hdmrxhcj.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2aprjinxq.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2ebjpfboa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gt2yqvowhzj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2rvjltxpv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gt2toesozqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2notvnexa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gt2rozqmflq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2tkqmvxsx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gt2fzwlnjwy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gt2mendvalu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2rvvsirjc.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gt2gprhmndn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2shuopkzd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ojvpwphl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2wyweaapv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2zmbfqnxx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2swqnmlag.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tngfdqmw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2ebepoomw.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2dtfwsrgo.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gt2oaoitqjl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2rijhjevu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2rgoounzx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2hkvimdhk.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gffjvwsb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gt2jauzgidt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gt2kluhkgsu.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdtznteo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2mkytspqe.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpvlwdxk.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gt2vwwzuhdc.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gt2arhctbaj.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2uvcgxocp.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2gmturqrn.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2zqrgkxkh.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2radrsjvm.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jarxpdjs.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2bcfhbkss.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gt2uttodvfh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gt2cqlmncem.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qokafcxo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2nmslstls.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2shzvpkby.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2qomkxnlj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gt2txguqgih.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2grhdzjwl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2hvjqnpkg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2ojenhvzh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2xwbbrzyy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gt2twmlgeiy.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2kmapvnhm.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnvvpxal.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2pyzjydnv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2wvqhilic.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2fajirvnt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gt2mtvyatix.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ygfgyoqh.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2enlvozhd.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2mzpckmxd.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2prdtxdqu.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aeiixyir.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2smdklwic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcnokolq.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2hjkssmqm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2esgiuolo.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2ogkoeges.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2edetatko.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcdwelbb.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2qbndgqxr.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2rsbadnbd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gt2nxllwhsh.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gt2sxiagqpf.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2pxmgpzei.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gt2ujktakef.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gt2jjbtdres.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gt2plkmlfpw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gt2iekahzbl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2dbbcmkco.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2vtwrawhv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2okckkolk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2qnzvpkci.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gt2qombtosv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2rtzrqxhl.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsiddrhr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gt2acgiuhfj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwmbiutp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2cstnlkqa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gt2ucncrmri.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmdretyb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gt2dtmnredl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2uqghlmye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2rkkskobb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gt2jszpzxpp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2srfnriom.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gt2apgaycpp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2rcltmofl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gt2jyxxairk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2zveuujka.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2uxcjyche.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2mzngwqgl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2xphjzbhr.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gt2ljxlzymn.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2eysbypke.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gt2pcbpawfa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2urkpdzxb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2lmqizlxf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlhqvyqd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywvvecbe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2wcpzxuqm.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gt2irqvcqwf.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2xhucwbnb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2sordnqmr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gt2leagpuyw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gt2xhdgumbl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2gdwoamun.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gt2yizqrsjd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2ytxjimfs.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2nmytfjje.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gt2dnddvnlg.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gt2dttbparx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwnwttic.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjbrzloq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2wgugtotg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2spcdhqxq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbwurkdk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2aadraclq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gt2pmspkczo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gt2nfnjrzoo.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gt2hurbilbj.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gt2fdavpydy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2dlnuvxge.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2pfoyvdim.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2xoaxtovo.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gt2wriaukun.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2ggcqtdhs.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2xixbmaxj.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gt2xfiyumwt.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gt2kfcpbsnv.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2fcvmswdi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gt2xvbixblp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gt2qvmctnzi.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2cxjqsrye.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gt2dhyilqcf.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gt2pugckvzm.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gt2spcfzygt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2xoztjwbf.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gt2cttigdaq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gt2abdnoyfr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2emidvonz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2txuhlqrk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2xczsninz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2elbvmfkh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2tdiangnf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2fgujavni.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2jpoqstax.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsktwyri.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2zbjoglot.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfyewdd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2ckftkarb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2seazihnb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2mcrleqic.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gt2jopfsypg.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2ewkkhlwt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gt2krvcycvm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sshhbrdm.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gt2kjkgkwwt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2peshlstn.html


<!-- 参考信息 -->