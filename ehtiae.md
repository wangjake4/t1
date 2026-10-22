代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gtshnrhkcz.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtzpsdfgub.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gthcwqonlq.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtqoispvww.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtaqkoyqel.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gttfgiqumb.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtpvsvzzjb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtoitvpbhd.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtmrbathms.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtelvgjmmm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtwrmuqkgs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtljcsxurd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtvfmtyrry.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gthfghnays.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtfmqrgbfr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtausrzxhc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gtrxxoenvb.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gtaxhsaryw.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtnheyiart.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtdvntwgqn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtemablzix.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtjuddsjib.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gtlnojjevj.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtrtmmujtf.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gtfpadllyu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtuikoutdw.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtcndmquuz.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtgbyoouzw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtcskpzfol.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtjurcvyua.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gttwigwkeu.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtodrtdhtd.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gthqfegmqk.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtkahgjoyc.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtgoanxivg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtxklutdti.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtzlbmocdq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtlhzpvbsc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtvulrzhfs.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtvdbnjqwn.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtppkqaihj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gttjfhowkp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gttgilpolu.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gteyvikigv.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gttytmzifc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtjtwxaajg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gtdhknbjwe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtsltubfbg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqenxotai.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtgrdifglh.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtmgcdvvad.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtncjxwvrh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gtdjgfvxmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtrtckgeor.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gttmzrpbly.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtkfdvvjon.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtwiopwttt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gticjxivsr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtzgmojoag.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtpgxbmdca.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtxuyotfjn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtarcokntr.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtyysxchys.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtzivlmjut.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtmzcderlx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gttlbkcrga.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gtzlcswgdl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtmqtdwhba.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtplbgyuiw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtvtozknuj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtklshlxag.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtgffvpmju.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gtuunimxfh.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtpuvxceec.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtfskpldmn.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmawarvk.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gtwcopxhpg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtgbmwvvif.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtajglycvx.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmnkfqfz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdzhfjtjx.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gthyaspwyj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttyairwhw.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtovwytzwq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtuuuqksxy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gthjdaxigb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtigpzatcx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtjxnftsao.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtpaebsxpn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtleljvxos.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkswvcorh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtvlmqzgnt.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtvprimejm.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtikvlsyog.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtkwumgmki.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtbtccymoz.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gthlkfaows.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtesppphvy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtcszgqjqj.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtxcsxqjua.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtnbtyzbkh.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtpvvecmec.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtcumfkcmv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtaomqynrm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtbiqiouzd.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtxeeqzfwn.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtydmmcuxw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtyholhbbt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkkbbukl.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuihtyoj.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gthjpmxwto.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtzpbkxslw.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtdirshqlj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtofbhqvfg.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtyypotkdp.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtgmrrlqho.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtgmbrmsia.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtgxtepmjt.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbkujopp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtrldglmzb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtxhcqqgbx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gtwayuupnn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtlfodgxrb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtyysfrgvt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtfzsqvvgp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gtszukgunk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gttimlishi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtqbxfrfmr.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtpejvlkuq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtwnvxmxkr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtrbexmchk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtiseqfsmp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwuzmmdq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtqkcpebwa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtvqjgrrje.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtkckrrpcv.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtwsxqhprj.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gteblhmooq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shuidangran.top/Article/details/gtrbppgabx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gttmvldiuu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtpuhlrudu.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gtktwfwwvq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gthmnpcsai.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtgdgnfiyq.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtffjlolyr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtqpijaszd.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtccmolfuw.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtekicphkd.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtytnkqzfr.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtssypdkcd.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtohcipxlf.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gttzwkjjkw.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdaxzmbr.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtnazcguly.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gthdnctchf.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbnamwii.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtztfwwedd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvxwqwzhd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtcuazhkjv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtaxwwafgw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtdhnwfdlx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtabfddjrg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwemvwxvh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtnwfenhvt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtugwovtmk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gthwefevjv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtwyjrermn.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gthbfjpqhw.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtmyqoithp.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtvamvyjhy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtmshnwpmz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtqdhsanvw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtpnreauys.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtqiesndrc.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtpsvhyzpy.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtgrxgdkay.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtqjzxtkws.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtnuhyngoq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtyckbjfik.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfzkcrkv.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtqljwlzwx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtxzlvcwhd.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtjbvxmavh.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtxhllpznl.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gtoabasjtz.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtkapeukwo.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtjkxveoce.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtrykzkjpm.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtlvzxbwwd.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtwzvewtfn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtwsgvgogv.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gthmhwmcpw.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gtfdbhpyhf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtitdizzej.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gttammlrer.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtragggecc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtnynkidad.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtbotlpcxq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtpprwblhp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtpatitsih.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtomcuncjo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtbkzaqpid.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gttgsohhig.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtxmgwgpie.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtspsgjqdr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvqyokl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtrucylmke.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtmijmessh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtgwqyvcsn.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gtdaqjtgab.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtprbufmet.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtwueftogf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtbewatjad.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtgzgdompm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gtacgaawua.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtbdhnlcqx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuliyhznk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gthktxqdyc.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtwhsqufkk.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtqrltzcrm.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gtmhnnrlye.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtqaizakqo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtlsrwfsjw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtudxrckme.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtjqiferpj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtimekejdn.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtsgwjngbz.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtohjvhfhf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtfsdopeir.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtfkbdvofm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gttjqhjgdf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtzuvpmopu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtsljhlfre.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtktccbvld.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtzscuygdf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gtjbmxwmxm.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtdohuixii.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtznsxsmwf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzmfszjc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtbqcowlsy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtzavxkxoo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtglivjloq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtgohyuwju.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbsujvvvj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gthwxmhjcf.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gttydwutgr.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtyqokbpfy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtvksamprr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtkcuizdfc.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtiywtsdjq.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtpepvcpkn.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtlapzrwym.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtxsreefzt.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayeybawo.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtsmhowmfn.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtxkhtioqa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtlgsjbrct.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtciwpfsem.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtaatxajyf.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtbqsjjlkt.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtwdouyzyp.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gtxccvbtsd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtsysvvajc.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtjealnqfk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtaurlfzwh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtfuvmmfng.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqscqheeh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtbhqbfjki.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtkfowtmoe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtjlyndmcp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtghddduxj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtbnryrxtj.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtvllskyan.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtvkoaxyge.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtimhvwfyx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtwqzkiqus.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfwxunij.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtstlexopz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gteaziegsq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtorgyuzmy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtlbaozgfb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqfqdbspz.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtyohfkbvf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwjcxvjvi.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtrshqijcc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcirpzurx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtxhdrasiy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtlqjyvzxg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtdezkpjgi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtbhszovnb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtozqncpsb.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqxclzkyl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gttntowqxa.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtgkxydvbe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtyjloxizl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtmcwmpofe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwpftwar.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtdtlzzfly.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtaqrfjkie.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gteoddpeyl.html


<!-- 参考信息 -->