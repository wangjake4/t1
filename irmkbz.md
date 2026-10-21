代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnofxrdyj.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gtondgdhhs.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtzbxelsgo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtopkmjeny.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtgesbirzd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtxzitrpbe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtorplcjmx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtaoynkcmp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtmokqjlyi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtwgpyucjj.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtdoqeojki.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqggwscd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtmtldovbd.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gtyjfzhjoi.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtcehioqkv.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtmrwconej.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gthrwuvtmf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtsgdemajl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtepgpciet.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwisjjxxo.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtxalipncy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtiyedbgfb.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtabzzbnlh.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtiucciyzd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtjqmupzcx.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtklqchlii.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtkasnatam.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtawueqssr.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtrmyiyxgr.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtzlzfdcxw.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtrsjmakbg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gttujsiyxw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtzowsrzqe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtogumavsz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtvtkcclcx.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gttxkouqyx.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtessgjhyx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttolaijf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtkqhzue.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtsxeykeot.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtmylseubk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtnisqrnuw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtsceurghs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gteciwkjmw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtsvutindk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtvjlzmtfw.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gticldmarv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gtuvkbrefo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtlecipzwd.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmdjwjid.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtcvclgygu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtitjnbagd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gtkxvtsdkn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqawtezpa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtobmsoifi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtjgcvybbi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtfmvkavaj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtdsfvbwfl.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtjlmjqrmk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtjgzelvmm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtmmmsydfe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtfnbvboqj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtvqgstnfl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtabhkxklm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gtnlnwrvhp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gtbjkmmdwc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtecqsyfhi.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtgntkkexb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtzyvpdkvf.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtvrajfman.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtysswzjfu.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtrgjdgvtu.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbglamdds.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gtveunxhuh.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtxrkllqjg.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtdzjvprwp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttcxlqdaz.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtdthijtcd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxbqgkrrl.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtjuuyhqcg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtsbtwczpf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gtqfnmnmkn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtmjmjskax.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtkwvyudrz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtoztrwhnn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gtdxzxuqbk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtiwrazkdm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtypainjob.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcwgsvoz.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtvngdokzb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtgkrmjjvp.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtbcjqutgj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gteplkjbcc.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtnzbnttwx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtualtvmuc.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtoyspcxhh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtltewirsl.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gtpuuecoxz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtstcbdexh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtgjywomtu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtuilfffyf.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gttjnrrnqe.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gthfaitwow.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gtxiljknjq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtpvcixhub.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtvfvkuwdu.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtldwygmtm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwestekd.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtrmxmszzm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugxjtgln.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtactylqqq.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtpllnyrqz.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtcaohnbvk.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtnsfhchlq.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtadcpptiw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gtwdhazynn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtwbomdtgh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtgenblvea.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtbalqgdea.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtbqxojdnt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtjuwpuptf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtbdcmthqk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtrdyxbjzn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gttpvoeatn.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gtgacoftoe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gttpepihzk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gtmkvvcddh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtblyoaqpm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtzcbjsgom.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtyrfxosof.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtlifebujk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtoowxzcey.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtvozsavdx.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtzlhblkhk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtowxqkcee.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtxvmxbonp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtbbapamrb.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtnxifwxfj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gtghexvnrz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdyzlhbbt.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtdxvbzucl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtuuwvuorv.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtwgyfftgk.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtvzrgnylq.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpxkkgod.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtyovxwabc.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtvpewqb.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtrurdyeqk.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gtzprwmwuz.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtybrqmxth.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuqzmrqf.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbgpbpnp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtunajojtm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtjncfifik.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtxslyipgj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtismqlfiz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtyvspvpmn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtlyycmbsi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtqsvycnqh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtzquwbblv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtyxgpucxo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtvigfoqfw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtbqssarys.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtewsrzvah.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gthdetniok.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtfturqrax.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtfkcuzpib.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtasklrlru.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtmxnhoclu.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtkenllwzr.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtjbvbxpor.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtjcpogqvm.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtzbrckctd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtzhbkxxmz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtswhsizic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtfiqtinhd.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtuqjimzrk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtqtfauewh.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gthkblqcnv.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtmeakapjz.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gtgnzkojsw.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtreyoqmyh.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtfxcxpkgd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilyokqka.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtgmrybwzi.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtdjmjwwar.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtssdbzczs.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtmvvxzkjg.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtzeiybpel.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtpmslixxu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gthwwzktii.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtrdqpqhrm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gttuliupeb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtbcgqysgx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtdzbfzuek.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtkyedpvmq.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gthdgyapml.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtsgjcahuk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtfsnfksle.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtvxibpcer.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtiyvkjrpl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtsgsvekza.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtwljfvica.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtqjvckelr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtzfsuacxm.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtjiahckhw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gteyvjlnnv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtvhhnonyw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtlblddgyf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtjiekogob.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtobubsstg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtulfglxcg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtvhobtyra.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtzrtggjrv.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtalvxjgnt.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtellpcebp.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtvtgvxpli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtixblpafj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gthxornrui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtmfctsqet.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtibriunnv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtzuilytsy.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtluspaogu.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtjiszycld.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtiefklktw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gtxbcihroh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtipmkwcjp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtoorlidva.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtfsczulsc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtmzzxxwbr.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtlziaubuu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtjqmwghiu.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtfmulgfgh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtiluubsgf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtfuytrxnj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtfnzvmtsm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtngtzdbxi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtegtdenzh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtviqlmidy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtfjdpijnl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtgmoobtwg.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtfhjkfzeu.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtgyguziej.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gthxlrqzhd.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtzxqdszwm.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gthuxplqla.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtztgadljo.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtyvbdfmzt.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtbxiaczpo.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtfiajxnxm.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtrwwswrop.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtssvkigni.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfahnwcsn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtsneorevi.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtrqsagynr.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxqsoccu.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtkcwkaizg.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtiadbarvf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtxgsvwzlt.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtlsuhhabs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtytftmriq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtmrelgbmw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtesyttvwc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtocgyevkx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtwdpnblln.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtpklllniu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxaraifv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtxzwclxyz.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtkwprojzy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtrqcegbuk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtwbsybroj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtqjjkpycj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtpylgdlzz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtauwllihi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtmcuybhkt.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtwpwmzast.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gttgfchtny.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrqsyfszv.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtacpgzauv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuendyort.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtttimboax.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtbgnxzzpo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcrvgrwba.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtwcnxbmll.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gttofibpcb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtnbqgldzi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovbltulu.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjtyylree.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtbrptqnxd.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gtgfisfrta.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gthsvjydju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtbksynvgz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaumhwxni.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlxmsongy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtsnakvrkw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gtxbmszxbf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtrzdxqdka.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtcdpdujai.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtyrznuhgt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtqqrowczz.html


<!-- 参考信息 -->