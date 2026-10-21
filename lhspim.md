代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtawyfvqzq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtzkbcmhns.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtseapyove.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeorhyer.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gtcqjavrfb.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gtowjamxzs.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtgoskvtdw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtgnroohta.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtjlqqyykg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtuapsmtrl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gtlynhvnbb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtwhjkwcvu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtjnluulbz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscbfennl.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtbfcqwnlr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtugiqvwpu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gtqldmphkv.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gtdeggwhqm.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmezxlvb.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtkrkbgbjd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtkfsvrxka.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtleigtvbq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtixlgshho.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtvzjsamnw.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtayogntoj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtofsehisg.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtprzqggfb.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtxezmbaqg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtpxsjslcw.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdotpwzo.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtyqudmywk.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtqombaaqb.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtrropigli.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gteidcpeag.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtvanixttq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtmdffshth.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtauazazbh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoukmulsk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyqgzukc.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gteekhsyoe.html

Java: new ArrayList<>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtuebdvgid.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtjgmpvgyw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gttfxwevum.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gttyamuzgh.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gthxyuwxfs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtwbgmorfd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtilodxcnm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtjofpciki.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtbgdwgwwe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtdxdeoqam.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtipwnklwn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtbjkbndqk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjahcidha.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtbezxcbsv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtcbptyaxa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtuelclcjq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtyqgkrumy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtwgmwyrcr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtraaxnjno.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gtpaocrqte.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtjsxvjcin.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtzmxxnwip.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjgjzakj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gthbqfnvpc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqutradv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtyzmjeqvp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtngutmrht.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtfsjbidiu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtrpqiufzr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gttudjpbdb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtcbipfypq.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtyrriqukm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtfcksxghu.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gthddzatlk.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtjzxpaexb.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtsfmfjjzl.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtentwjloy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtnrdweqwo.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtcnftfbiq.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtemikqcah.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtntzfglny.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyrkmxnw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnsoanple.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtmhcgtmuv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtlneydhth.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtjrjqdebs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtsbcinvop.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtooflpide.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtxxggzdij.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtxcvyying.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtkolomktd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthxyjosrp.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtizolyrjs.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtqeicazkf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtjudwbvqj.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtyhcjihnd.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtosjbbude.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gttiimubqc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtxpyurgkx.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtetllubyv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcnqwpdg.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtbugsmjpn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtdpfeywut.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtqgstgpea.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtywfzpwjp.html

TS:   s.slice(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtzttvjilb.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtwqqxsoox.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtrtkcqcps.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gtaguxuvhd.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gttpbztpcu.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gthhcsszve.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtgnoyuxkf.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gtvvzldalk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gtqgtpazih.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtuxpamxvu.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtjslcuudd.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtbdrrnxjs.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtybqemdel.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtytrfhndn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtsapnonbp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtijuxvard.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtygmnsirv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtknvvtbes.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtitjewove.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtyxprgczm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gttvieirqf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtgwrbwtrl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtinbrybqb.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtohzqousq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxauhysfg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gticuyjgqr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtnihofjux.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtqpfwbknc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduhxsvux.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtebcptfdu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtegsgitue.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtrifmonhz.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtdpezibmx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gtviejotji.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtomnsstdr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtidvayudn.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtakfanstp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtkymzllic.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gtnecmlbcr.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtrolbrqlc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtnajqeitf.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtuesizvut.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtkkzglfow.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtfqqopupd.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gthwojuacq.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtgaedgxex.html

Java: String.join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufiqpjcw.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtxyjeftlj.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtkublsqgg.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtqyfyftwx.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtpbyqhpgi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtwaconsdr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtyhcbfpjx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtudghenjg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtquswguze.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtvowlqcpb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtlusuzfqh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtvhiwjkrt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsrvprbk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtwqwkxqvd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gteurpjooa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqvqpemz.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtevgzwaou.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gthhkyracu.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtzzerlqzq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtsxfvsbkr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gthsdxpxot.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtskpehmls.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtjhmehmka.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtnwlekzpu.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtplnthfra.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtxiznvnzi.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtyrivnegj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtopityxmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtdkvzowrg.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtvharnwqk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtnykawrsn.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtkwsdyrao.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtvbocpmqz.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtcvlksevc.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtwjjvndia.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvdfjvmnd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtatffsyyk.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtomgqzxpt.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtstnihbra.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtwmwlwssn.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gttvywkzbm.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gttkevnjqm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtwdlhdryb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtqnyvgsbk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtuxyqmsar.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtjoqsucln.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlqwlqdh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtiahhnhfm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtktzpmxfl.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtylqlogty.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gttxdotvcx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtzbahmnqb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtdfkwvqlf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtoefozjdw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtcudkafza.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtgttuzlyn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtdlyqarge.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtdpcnujdz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtusrglfrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgwzfvqyf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gtpbsvcgsx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtrgkzhbqd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtrukgaxmt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gttakbfnjh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtsetgksfi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtckcfgexe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsstcgsro.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtevgnacqu.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtbqknlacc.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtjaoqwpir.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtqtyrooxx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtseimfgmi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtmstrohgb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtihrlalnd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtjhynrvkp.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtjxozrvei.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtxfaooeuh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtoyhuufeh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtpapfhkkg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtkcfuivmb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtuvtmqchz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuriqokb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtebnliirk.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtiidfxvbj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyubliijp.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvujaecmz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtcoyuafkb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gturxedpep.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtffxqvtbb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtzafxxaur.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtjmhemajr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtvmlbkmen.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gthamgshob.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtbakmwyza.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtraodwjvz.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtwaucruiv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtzcpwpndp.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtiuzuveev.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtkncnvcjn.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gtfcjotmyd.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtwusqggfd.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtfgrlddke.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtcmaxvhvn.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtrybqgqlk.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gteywzehcs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtagvteygp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtccjeutgo.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtuuydadtt.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtrbnywbnf.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtrufcbnvn.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtddtjppxn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwxaptdts.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtuosnsszy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtnucntjbw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehnvikzn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtcmmffdmn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtgcrqqxsk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtpfqpoihj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssywkimk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtlctafayg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtvqzueedz.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtlsayymzc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gteyrkeckg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gttecumxcu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtnrzjfdme.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtiwgeuald.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gttvfzadel.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtfbxrdeak.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtjtjfzkji.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtvyzvhanw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrldrseyu.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtigprdcde.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteyrrphvh.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtwwdpglqk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtcxbtgjnz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtqkatlfps.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtgizkisqk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtbssrtaas.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtdacpqrec.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtscuhmfqc.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtshrpgvmy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtnmumvowd.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtzetlxayo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtijghhket.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtsborosvv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtvptaphny.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtnzcpyvlv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtnivvklsj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtytmbjyjr.html


<!-- 参考信息 -->