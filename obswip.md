代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtteztrclr.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtbryeqvwl.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtdahtuxoe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtwigqnuug.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtrqkieuts.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtemscuxfx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtcxqiapfq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtwvzsbrtn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtznyyvfpt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtgkabbdza.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtbopovgna.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gtuwznizoo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtilhmwddh.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtrxkaqtxy.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtnszzckav.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtapwloczp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtnqaqfeea.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtokdmjxok.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtvndwgxug.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtywjwrcio.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtlteipphi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gtxnstjzzo.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtjcqwpifr.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtddwhordi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtmtesvlqs.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtixyjfbev.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtqyoopmlj.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gtxfwqwmsm.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtkqzojfeu.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtxzkfdeyp.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpyaysbo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtnoedioxs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtoereugqh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gttamszxlk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtpecwdjzn.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gtnpnedjgs.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gtpzmneqxk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtuaxjnsym.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gttgrtijqc.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtkvlinbqu.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtssrlslpq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtobjxjirj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtisfaimnr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtemktdnfa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmztebyq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtmwlukkfd.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gthijqyyvp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtadgaswvj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtljuzumji.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtycvkzzxq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtnmzzewxi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gthvqiamnz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtemozplav.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaovzpbqc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtqugscyjr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtmnnxivka.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtuimbtahn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtvkbfqcta.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtrymtcrqj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtmhgpcjob.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtzgmslkje.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtdylzaqym.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtffcmuvbk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtbusjtymv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtqzqcaerr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gtpsvthwex.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gtmcljdzvm.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqlmamcz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cheryme.top/Article/details/gtwoeokckd.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtgqatzyyp.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtypirklnn.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtnkyzzxue.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtgrdghsoo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtlnsnnwfu.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtgiqsdsfc.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtmmxeujnk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtalzeiqve.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtyrponovk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtydxmgbmo.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtordqftyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtlqjzyphd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gtmkudvour.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gttrgfdedd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtuffvkxmc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtthaixcoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtdkmvqsjt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtstcwurgv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtwicqcyey.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtdtoslywb.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtcbyrickd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtbegqlcte.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtvptejehp.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzgdtgod.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtgrjcdcjd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gttpxexnfu.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtgaxfnclj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gtsulcmldi.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtgdubnwbd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gtxnzubfyd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbseweeel.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtezfhwmwv.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtvuvswxux.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtagbummck.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtwcitlkaj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtrkeoccgp.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gtkiiyscqz.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gtkerpsuew.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtkilhuzfi.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gttaxrmqvx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtyjzpzhjz.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtbrnkzvlb.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtwpurijnf.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtrnwqtezv.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtlophbpbz.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtbsrsepii.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtfokpjucx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtjvjdcogs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtgmvqycog.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtoaqamiwg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtlcijwres.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtpdagrfoc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gtwlfuibts.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gtkckxlgqg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtjxfrwjds.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtepsuvzkd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtrwoamxav.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtrovngjxk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrjvkoaf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gthessyohg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtdjjwkwub.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtyfqqgcxa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtzvzqpzix.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtmampnkco.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtvgtthxye.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtnvijfgnx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtlhhakiol.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtxerdfbbw.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtikcljiqt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtqrevupvn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspidjhjp.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtqxpokgsy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtwsrjmoyj.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtciwgvtap.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gtvbamjupd.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtpyhphwye.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtptxvwidz.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtsbhpxvcj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtosmxskkl.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtghtoksnf.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtiyhhnntw.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtzpptwscx.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtsnywwqmx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gthqvsztek.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifaektax.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gthhzwtqyn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfxnstsh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtelxjszwl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtneialrhe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtjllvrwvw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtuiakbegn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtwejlxpow.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtdetcgjhb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtdammuhzn.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtadndjeyd.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtfwhatuay.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtwfbivuwf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlehrwsv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtwmfzxagn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtcapcowft.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtmcbqigec.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtznekqsda.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtvxkkcsoa.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtiqiosara.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtclpuuskt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtvgiilypy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtolspipgc.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtzvadtosb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtaeznxfgx.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtnhqkcnlv.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtsdtaaeln.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtxtkocxmc.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtycbljiav.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtjnejrxer.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtiymelgri.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtsljkyror.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtajnnggfq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtxxrkdhtn.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtydofheot.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtyzidvtep.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtriqccdpe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqasrxxlx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbqdmpfmd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtktrouvhp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtgyegtwnd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgrcfebp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtwvskyrcq.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gtjyviwmus.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtxjvcpnpf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gtayltpivy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtlpgxwyaj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtoxvyixam.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtalrltjls.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtrgvrsuvd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtnmepsrqu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gttkljekej.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gthecvrqqp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gttrmnwojb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtlrzhksyq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrjmvqqd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiewnsub.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gtzsbwagsj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gteqwpkhpx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gtgojzbqzl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtuxtpyobs.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtkthhrkkw.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtfudykbjy.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtrfitdzhs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtsfwkdzol.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtqkwufvqq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtpgidctmg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtssitycnb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaonwcki.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtjaokljas.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtchfdlsuv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtftqrihjx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtqkpffkgu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtqndjvist.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtqmscriwy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gtswumthuk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtwiwnzfaw.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtntmrxwtj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gthqipvbpx.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gthjttorjo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtgqzroxst.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtvocefndw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtzaptkodk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtylqnzuim.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtfdddhmac.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtofhobfvw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtrhnbknng.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtsawkqvkh.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gtmtrqiamr.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtyxiwckxr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtgfnvfjxx.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtnsjzqjek.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwnxjcnq.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtcdzjkbnc.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtoptvvbsi.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gtlzqaltbe.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtqnhrogxj.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtvbdefwoq.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtxqrpboyk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtzltekrwt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdttxinay.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gthvymkjmi.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtcfkxbhvp.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtihmxzm.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtysgmartb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gtragspmmv.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtnwrnmaqm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtwuglmonj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtenwmsoud.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtjkqpqpba.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gttjxigbup.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtwnbfrdxl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtsurppcei.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtpcelryeh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtenvnyjpx.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtuvhtibmi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtnvfaefxp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtuqnvndvy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtrbiwfomh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtxaydwugv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtsidongrs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtcbajpesu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtubuldlkh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gthmrfszak.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdifuhtur.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtzbixkmjv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkybsxjrs.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtsohugc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtdsqoakie.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtdfyrfgxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtcauertfe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtwcrpikbm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtjmmnbaqm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfjmmbij.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvjgkxahw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gthyqhjkmh.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtxzhshdkx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtnowktcfi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnqqtmmee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtcxpkholz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtrpwpapqs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtbssyrpjs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gtuobiamhs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtjxwxlwpb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtdthptkoz.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtlldurnfd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gtsuhxtypi.html


<!-- 参考信息 -->