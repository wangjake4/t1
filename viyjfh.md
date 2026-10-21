代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gttbtugkqy.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtdhzimqqu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gtnzeqezdp.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtdaurjabf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtzeymxfsc.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtydurxnpj.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtlebjkasg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtmqnrdlpf.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtemqarndj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtnproqayk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gtlhttzvli.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndrubzio.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtlprwmzls.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gttcxmhqae.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gtcmpxwfha.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gticxxtqpv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtjymfzrgm.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gtufqkebds.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtajmxopmy.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtroiffpjh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtcknrdlka.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtiinhuetp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtladoqvzi.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtwbohugkv.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtgxsqphjn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtzsstvcom.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtyeepgzgn.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtzdwogbqp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtfpcixotb.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtrabibixi.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtvxevotkj.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtddzgmmbd.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtqdtfbiid.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtioqpwdau.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gthcwxoobr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtouzxvzfn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtiedbliro.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtfiuuabfy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtqpfxetoj.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtiuvqjvye.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtlobotsci.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtrxazbztf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gtmahhugoo.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdvdxqcl.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gtzkchvpqt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtnrfvxgwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtdfpwnfco.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtnardgilx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtxowerfqw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtsdccqrly.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtzdgdtigp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gttskyakxf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtsnglexio.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gtbewfucub.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtjphiqidj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtteoyouqn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmszrnjap.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtshtyetqp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gthvfzcxit.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtykiexfvr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtwxegehxd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtsdkoqbdy.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtuimdvseh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtxgwikryq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtfjlonpcm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtdxmoxwge.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtuofsquef.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtithhwmhb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtnkrxhkzh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtscgwkkmm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtbjrfevrh.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtfcydfosc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtdwyeqgzi.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtosudqbec.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtebvoijja.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtyguqfxgp.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtkbxonocu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtaikjqrbb.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtseliupiu.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtrbxuvyur.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtitulgmis.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtkbxnyuma.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnxpjovor.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtngmivofb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtkmugnnjw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtqvfllwxf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtsptelsel.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtsmwghqde.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtlrfwdkvh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gtvlgxazmr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtxqodrljo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtmpylrhfc.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtlbwcltyy.html

Py:   "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtmidgwhhj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtfesiqsyr.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtjuanohtq.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtbacvxaer.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtrufcvydu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gtarroeykq.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtnhpcvdle.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtfjroxsqy.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtclqvypfw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtqostyjjf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtautxwyto.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtpulyxjfo.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtutckojmy.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtfdnrfdyp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtircaxzpo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtuvxxpckw.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtggjolkvg.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gtkummexuo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtsayvxmas.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtqulnpjgb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtpdqgotkn.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtkwlxuomn.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtrllcwghp.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtbhniloef.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtyhtxdnst.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtztjwzrlp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtlwnbdffu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gttaaeknea.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtuxlbmlnk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtjpkndwyi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtuaignxbt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtitcqdhzp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtkwnntxec.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtdybiyqum.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtdiejggyg.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtaqlarqcv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtttxclgqv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gtrznyhylf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtrrxlieie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtalpfhkbb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtpscflnpv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtlgkpzidc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtbdquluzf.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtldncfnij.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtlhvepmbl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtqkunfznc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtytxousrp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gthxkcdgyp.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gtsuvhnjia.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gttudmyhiu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtdgbybxwh.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtehnblppa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtyadhzoga.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtgigeescc.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtakwbhuiz.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtstatxxtn.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtbzaroyyq.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtnooqpgkp.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtvwblgnja.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtfibqnffv.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtvaplalcf.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtezbqkgeq.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gtovfkplvk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtqxenhjug.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtqfrzzefv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gthxrixylo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtythxjsco.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtxejvnnxp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtkxsxtfgc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtjyogxajy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtayyoifmq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslejblgg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtzbqvohre.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtrexubuhj.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtkcrspfas.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtveudouyi.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtxjnzyvpe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtwlsvkazq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtmknwabom.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtjadedndm.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtedvjzeqp.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtxwmlmnxf.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtcnuqxpvr.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfuvmirbf.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtqvgyshxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtrkawajqe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gttymnfbnz.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtusmejvrj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtaldpuqpj.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtvnerrjuu.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtsyxuqull.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtgubbqcvb.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtikvasfdb.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtcdxrdoph.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzywhqijw.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtrtdvohao.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtmbsovkba.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtxnkbbnmc.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtouqypxjf.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtuaeswlan.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtcsapapcg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkymcqget.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtqupqfwds.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtwclblhlv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtukfoubis.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpspfjqn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtopydceto.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gtashazclb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtusxswben.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gtserfmaaw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtqpbqrhtu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtyiknhzbb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtcnnhbjgn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtdksullxd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtsrszcjlp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhzzlxci.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtdmfzwrex.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtgqgxhmvt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipsajokz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtsqzsfllh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtwimnncvm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtzcbvufex.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtogkxezjn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtvakxkeft.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtnhbpbxgh.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtwitqlfcb.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtrlgpszfz.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtpcqrcwny.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtwkpajyjv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtiujuydch.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtrbugctfw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtfixuxezu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtsqjrtolg.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtiqfvsfxq.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtdkpuedhh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtnjggoegd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtilrduibd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gthdtohtfu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtxuekwhbw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllvoaenm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtooeoekgv.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtypqdkbuc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtgfcxwuul.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtpituxdwx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtybpdomqc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtnocbuvvz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gttgrqnmfj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtanbdmdpo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtwbmfpqfp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtswxbyopt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gtwduaatnl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtmzuzgrza.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhuhkkxg.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtiizkeqjs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtvsmfpniq.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtmfjthioi.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtqeyzrpub.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtnnsntlvb.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gtjlmmcman.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtqmhlzyrj.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtpoprtaxu.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gthiktxcwt.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtwnxcnspz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtqzpbzrve.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gthzlxkbgg.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtqhslqcsg.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtiimyeqrf.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtxeqfaabh.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtabdyvwpj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtivgbssnh.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtkujpokgy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtdokmhdyh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtcmozeejg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsvwsaof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtzqeomfmw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtxlbpzwgj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtiqhbwueq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtzwydgijh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtoatqzgfx.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtrxzpbnpa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtdyvuvhru.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gticvjtmfw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebgbhkyy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtysvbscjk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtlhucpsmk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtcfseqgcu.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtxjukyycf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtsvnwnufs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyvfebhhu.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtrslipfju.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnnxfocwl.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtymauzhvc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gtivsbqvvt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtimbdmllr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gteovfxook.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtsbywqasi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtyavosvvm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtowcbljky.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtwpyzptsh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtbpigdpya.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtwvducoky.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtjahaqlid.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtbisiiwig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtnvurrfpp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtjoqmbqmf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtrhusxnhd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gtuecoqkwh.html


<!-- 参考信息 -->