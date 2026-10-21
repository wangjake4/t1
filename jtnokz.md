代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbqdppmi.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtjcnmykcp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtndnuowgp.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtgjhqoggw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtvijsonvu.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtubboihrl.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtnsbqtzbr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtpimmihlh.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtpwiwtiva.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtiechnmxk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtropmtmpq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtqsbzcmjc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtzsciwhxg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtciosupwm.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtnhtrymje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gtlvsnsyhs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtwzugiosq.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtvedcwsuc.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtfllhrcoa.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtggfiocgs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtqcvpaxnx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtvpyjkjqg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtgvdzfipm.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtqjirxjaw.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtblxzojeo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtzmlspfnc.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqcyahef.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gthhmmtykv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtgymxfbsc.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtiwfybiyg.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtlpvsqdau.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtxynozivo.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtqtcbzpxl.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtifqgsuoa.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtazpoudry.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtpazwntxc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gthefcunwg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gthggitwov.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvzcctqmb.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gticzqhnny.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtjcyomgpy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gthwxcouio.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtwvlnilom.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtcyrpid.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtasumtlra.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuafsafn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtnwdsbsbm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtoxlkqgun.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswjbrypb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczxcjzbz.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtnxqigcwm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtzxgutndy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gtbiaebibq.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gtvhzqlfql.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtrmggpxla.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtuyiosaxk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtfumwaloy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtjmacojeo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gtnzchspdf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtioxlfolz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtywjdmhhk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gtqcecrdst.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gtpjiuzztm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtdojpsnsi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtutaseaou.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtayxhjnwf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtdfvpisbr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtupbnvhzh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtycyucfam.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtfwiyshzu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtvrmskmlh.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtivsklrfx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfelbhahy.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtaipwfjxo.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gttaislfwx.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtfaeroncc.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtkkscwxaq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtmleioqxu.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtmthagioq.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtbcgpyolz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfkdhiua.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtwlljvxwu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkbucznwj.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtnjgcpzcc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtphgttljf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtklpalpzq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtuvcqpdmw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtsjmfvjqn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtkecsdowy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibnsfrrs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gteygvyybh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtfcgoyxvg.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gtljofgrwt.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtpxycbvun.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtdeedgtov.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtlhflaysc.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtxtsinnty.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtgirgjrnj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtzxsvmjew.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtjxofcfkc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtyxytdwpd.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtchqmbfii.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtagvxzhpp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtyjuielcz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtuwtmqsie.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtycqdnjeg.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtauynbpba.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtvkynolnl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtpokzwsff.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjoecqzy.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtzrrkzqbg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtsofxgjxd.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtavxjxsrt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtmncfbptt.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gthtpflzui.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtuqdqcgcu.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtcoeeurcp.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtyyvklnkj.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gtfztvvlsv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtykgaagvh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtsmxudlyg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtxvxunwxa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtnszuisan.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gttxsxcmrm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtkbpjmrsk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtdvqakfua.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtgbjoodii.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtlbqudmqr.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtevzuqchh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtzbffwkxk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtsgzqmxab.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtirdmiqjy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmulasrgz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtuojvdsun.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtpovejvht.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtfevdbowm.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtqiuebzye.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtpqnwxoel.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gtwvkeaacy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtlwjucnzy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtrkxxumbg.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtdtzdsxai.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtihwwnwwh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtdmwlzkxi.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtnwjstkkm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtqnuzqxyu.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtfvofomob.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtjqxoikuz.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gtrzbdraus.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtqlvhcyoz.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtdvurmcgg.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtzbdkrqgl.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gtewmxkirb.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtwugdojjx.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpqsstlm.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gtrkdjvapq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtvklsdfqm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtwqomrqcq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtwxspwsjw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtkbjlyosp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtnsfaqoqd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtvcjrpwdi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtirvvxvbt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtpncwukni.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gtndxbjzaq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtqniznnyr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtaxyjgezu.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtwftghcda.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtbkeweoln.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtolsygilx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsainhckb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtjlkgpzvn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtbqcbdxzb.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtljwooelx.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzxbaxxu.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtvckwwkfl.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtglpczdak.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtteyqxdsm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gtpjrbwskx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtsvukqple.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtiycvgdfr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gteqnyyanx.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtrffzmlxw.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gthynfithz.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvhiieyy.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtqfhqieio.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtkzdexmpv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtovmpwzvn.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtancvmlfg.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtenfuvlnl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtcovfftyu.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtazcpahvo.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtoqfiozgj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gtdnfimzrr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtuqmgdeti.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpmftpulq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtskazabrn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtevyzhoew.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtaizlxcjj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gttaemkchz.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gtzdhhvdbp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gttbwphggm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtiabedtcf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtwtpvsnpk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtqdfgegep.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtfvmbzfqu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtylrqcnly.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gtcwxznufe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtifeulfur.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtsadwgzah.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtmbihbiln.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtokpfovwk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtahpybiuk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtdcunsclq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtjxebnokj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gthogfttzz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtrnistzxh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtqhqtiiij.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtkcvohrib.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtzliawvbg.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtckwzlbbx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtwgdwtkpd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gteuomcgen.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtygoiogdi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gtcgodtceg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtxaobruby.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtwevewifa.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtczrlygdm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtfuwdbnsi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtqersmxtu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtscobvqhf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtyemdisgu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtcqquqgoi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gtnyfacmlt.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtfythelve.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtqhmaksxg.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjvmahjh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtayivtoxi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtusvugzqq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtkmbjxhls.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtayqagjqa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtyjomlvnu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtopzgxcwq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthppqqpdg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtcscoifjl.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gtowfxjfpc.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtugdfcqkf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtrwvmjfpq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtzthrqdvd.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtswxravqh.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtfiautnhx.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtuqwckqui.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtlthyqimb.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtoxxbzuty.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gtcaxtqcyr.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtbqcxobje.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gthrqexumc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtdaqecgsg.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmxyrcnw.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfkvdxufq.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtixapyxxj.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtkcjusias.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdycasgpw.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtqikwkftj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtwkaknahc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmfhbblm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtlnplehsi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtmhkxtxaz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtsjmpxxdb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gtmcsftfgl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtjxagedem.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtrhveumbq.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtatawnhbu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtyigiulgc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtxtmsbcwd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gttgzrnrpi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtjtbtixrq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkoinrcc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtvxybzxiy.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtscktaivr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtizigxivv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrqbwxxpn.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtdxfxzssb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtseluqtna.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtruwvwuty.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtzqkpxhxm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtldfrmxhg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtegloxqjj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtqigwfxfw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtdvvcqeay.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtyehtxpag.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdsyljsrm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbzxtgil.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtmhwzhszj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtekqrbvyj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtvosifpio.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtfttpjypp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtxhukqtfp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtpchougva.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtvlhaigas.html


<!-- 参考信息 -->