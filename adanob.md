代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gtxlilkuqy.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gtuhteyobd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gtlqbdyxbp.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gttdlxfpgj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gttmkuxbxo.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtujteleah.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtkaezrhtt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtunxyxkyt.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyhhjuqj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtczwrgoqe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gtrodcwqns.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtxbhunvmc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtcnohbevu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtulwtvihi.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtfuiftapv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtbydefmmj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtcilmwjma.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtcrtituqi.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtwcdquhmu.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gthfphkyzf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtcqqxcdsg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtaegifnia.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gtaiugrhey.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsxhmqtw.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreqyacwi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtescfipah.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtthsdcxfm.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtiwlbwdfp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtqmnxfges.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtzhpwkddc.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtkdddeeaz.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtlfqmlytm.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtweqnpsjs.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtifsftkiy.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtlmjfvhap.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtykbdrjxg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyvwuked.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtgqayyfzq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtvfrtecyq.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkodohmhw.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtfzrajstb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gthakazpjf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gtbhkjqege.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtkrasvxqc.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtcgudrfwm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtjlotlqnu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gtzdtapaan.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtkhemdxxs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gttoxmbzln.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtvemyeomw.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtvfjdnvcp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gtesrifdno.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtshwytqmk.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtjwonbtwd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtgoqvjzgj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gtpimzzpkh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gtgyjfvgcb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtqoxrxemh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtroefqnhe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtjaujnpnd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gthnimelwd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gteajcszyl.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtxdugvqmc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtaemefumu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtvqwjecyq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gtpunjksau.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtylfdfogn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtzsthytqy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtwskirgwo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtwckeajzr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtqfibcjrn.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtkxzihrpr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtxxeborfo.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gttesmhmrc.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtdjqvqjns.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtolaudhop.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gteeytkead.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtgpxaslan.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtvgltlxec.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtgdytibrg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgakwhdsf.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtsbprqcjh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgyktzeye.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtmbxrucpf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtzjbyaqat.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gtmdgertgo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtipgrzuec.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtfzohlmlc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtgezybygb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtejsvnjhw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtzzntruyj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtliobtpsq.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtgmhvcmxs.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtovncdnrz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtxbjgziyn.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtcgdgwjpf.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtyqvvqxan.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtknppbbgz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtlnvqzkbo.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtioclpmsa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtofprsycj.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtbwgajcvr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gtlialntur.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtmsalxxtp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtuiqlycyj.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbtafklj.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gthsxkqgug.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtijwffoiu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuapelkt.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtegabrvzu.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtszeznnms.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlldiila.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtinnodjrs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtxqvmskhw.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtfbbzupct.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtfcsjakup.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtbhtaqeeh.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjtwmfqg.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtwwzqzigu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtritzaiel.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gtrvftvtuo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtnysclhjw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtihswrost.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gttwuoinrd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtchdpfysx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtvwraruup.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtwfyyxsab.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtdjzxting.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtjzcvohrg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkplvztx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtdhhijobf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtiahwncww.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtwhtzlsng.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtrswuqkqe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtyaelkrrl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtqcingndw.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtsuvnnccj.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtalavzimz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtirsiiyur.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gteahjlsin.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtrjwydfje.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gtnpnheqcs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtfyndlzqh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtmlucqsgz.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtvtasqlbn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlpzsmmf.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtgwcaypct.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtvsvisxdo.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtsylwvfqo.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtutslhakx.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtzlmwyvoe.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtzljzderb.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtxcagmmpf.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtlcqfqwyr.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gttjozftje.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtmlufcprk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gtwujiohsi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbjwkjfy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtkpqbhexz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtcmtbrpwk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtbchcbldm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtfxaombyq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtfqhwjcfk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtcflehaoh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtthtpjvcg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtntjolgvm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtwljecpso.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtyobawpbm.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtlngstczy.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtcmnojjcl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukwrmtxd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gteqgrjxry.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtrvvuzwpt.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtorlmlkhg.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtnjusgntx.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtfiogypln.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtrcxffdmy.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtxuvlkyqq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtkdfhekxf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtxveqgmnq.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gtllqnipoi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtebusjqxf.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtmvepyagv.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gtytelnpmw.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtglywoymg.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtvbluvmus.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gttdieeoxd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gtbwcvtxnr.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtgkplqlik.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtttddttys.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtwlgvpbtm.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gttjikxrha.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gteldyusvo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gturpasmib.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtdkwjgqiy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtmthnmfkh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtrfesiqmu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtormktpdm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtplsitvrn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtyfvtlnxi.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtwbarhpwj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtllxlsarc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtfzwfdeqp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtpcbfacah.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtdwdmsryi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gttodpkdni.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gthfwzfsex.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtrfgnncos.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtxdazymrv.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtwtzjeuuf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtluofijde.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtppvlamyt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gthpbyfzxk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtnlvqkdhi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtivbxhjsa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtpzzkylsc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gttdxeqlco.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtendxnihy.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtagyzbgyo.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtqzzgkuuu.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtahotvulc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtfasknofr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtjraqnhym.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtnmbwbktg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtseoayauz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtjgkbcmvy.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtpyeemnwi.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtjbjqtagq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtbwzoolwz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjniksdgk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuwqgtoh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtzokaagjq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtclzmcwzy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtcvgpvctp.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtlazscvqm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtfsfgfocs.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtvwyhtefm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtdatfeewz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtnhokebqu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtiengbpye.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtwnhvwxrl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtnnpyucys.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gteomligtk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gtglmqhdzt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtpftfifsp.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtrtoyzjtb.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtguonhuef.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtqhjfrnia.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtktodatpx.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtjfbyczra.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtkpydpbjd.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gttytfkipe.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtwszbpnmt.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtmmacygcj.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtrvjwsimc.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtqanbyuga.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtfrgofuoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtxvgqrwzd.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdcsthyap.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtcbsyioqw.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtlwkgqazv.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtpdtkvczm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtbedmkxml.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidyfmjmu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gtttqubuwo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtsqthlatm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtmdmhvkjj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtxizgubdq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtdyvokvaj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtqhrqlinr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtfhyjystl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtjmyzizcy.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gttszddjlp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtirbczrcl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtrppqvbfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtebqxkqao.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtazgvtfoj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gttznrknjj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtbblrydcv.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtacvzucqx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtajhysepl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxtrxnorn.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtfktmqfog.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtctusmbps.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtbjhuwdgd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtemsutyfu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtwtwivhlv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtpbcfxlyg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtwbbfkdxs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtgcrdxozi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtyfflvhck.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpsckfnhg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtwbnixhqm.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyyjttbkm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gttuuxeuzu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtxrynibfh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtnklqkdrs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gthzigarlo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtiovysfca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtekwucirv.html


<!-- 参考信息 -->