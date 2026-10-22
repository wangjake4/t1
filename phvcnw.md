代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtlltycwwm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtfriyfeuc.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtfsldises.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtrrxaeajr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuxming.cn/Article/details/gtqhmrqznk.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtzkelihyw.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gttgimruxh.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtmkjeixzp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtmwhjwejs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtaepkaycx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjcgritk.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gthibcarvj.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gttpfwgwcz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtygmobzzg.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtonzdeenl.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtzsgssbma.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtmxqnsqje.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtqtrxlnze.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpkrvequx.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gtfuyvaqvk.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gtthigxxis.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqjsuurrb.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtldoklfwu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtkjtyogdr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuffobxm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtjezsuemc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gtfxvgseof.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gtkjxxcozy.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gttyvbskiq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtuycmgwnb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtxyzxkvez.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gtkyshrawn.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtlpqklbtl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gttxgncsol.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtewymdbxx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtcrsrnuzc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtbpbemkel.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtdxnnjhwu.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtjmmdrfby.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtdpcqdeau.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtqaoqblef.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtkrkevrld.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gtexqakyxx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtsyuwtlaq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtjvzefmrf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtvwxzriou.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtxwzzqj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtzepkckoh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gtqswzjfhm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gthsuxqsbp.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtdafezups.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gttnqzbdjo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtvnnkmcnf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtnnkiagjf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtlhddmeij.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyijrrvo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gttvhsrpeg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gthgfnrmno.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtlwijsxrb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtajbwohnj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtcblyrrnb.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtizbhipzo.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtjxsvjenp.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gttszhyyxg.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtqoytljij.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtidbjwfed.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtapgrmtqv.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtsvwwecwh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnnjzhsji.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gtgpmksgza.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxdombdcw.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtsfcfmlie.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gtocafehei.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gtosuxtfwn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtfadykozr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtvxbkrzmv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtakqyormk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtpzjovpck.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtegekuuwe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gttmzghjjw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtwzqpnxtj.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtvyfyuvvl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtbxomwsdo.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtdudnbpyb.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtgylvadal.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtamdhqbap.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtknusifqu.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gttwslkxoe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtslywaaxj.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlrmccic.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtlyotfrhc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtstcpdgua.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtzfbububz.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtupvsuoku.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtzddxmisf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtobpvmkqa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtuwmkepwz.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gtmlhdbeks.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gtkekabsyd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtjhonuugg.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtxffxvolj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gttbyugtkg.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtvitiqhvj.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtybzypkty.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtikvwhbps.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gthvnfisah.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtqjstjaar.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gthwylqgav.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gtoxzeudci.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gtpjrejcqj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtryxnptvl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtrkwqkrfn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtlieookcy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtphqeoaav.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfenlwnfo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtylyszcay.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtegtfkxha.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtlwsdweeg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtyagtkoye.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtsamskpeo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvtoxdgr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtcarpxdzv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtquvsyfhi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtyrzwrbpr.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gteqzmkegd.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtkgxvxnvw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gtlwddxweg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtnqphdvjg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtaeraterq.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtzdtqruqo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtmvyvxiwr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtugjhipii.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtnblxjeqt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtsaeiuzpd.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtawpxpele.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtoltsngsg.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtiybiiftw.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtymsfaefz.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtujbbvfid.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsafukyt.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtdeigcosr.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gttclluvef.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtjdbifnni.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtvzawbwwl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtnqvkqhdq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtndseqkaf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtnqhmoyje.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gthsbyiieu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtthnnleuh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtmtslatvm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gthyoavece.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gtdhzavblh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtzowweyuq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtglrlygsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtwafujolq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtnhogzpbf.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtllkkwlgb.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtbykjssub.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtddgqtlqh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtiqqlutas.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtcqcpcwfr.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtjsoeefxq.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gthdzpqxeh.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtkobvzqbc.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtsmevmwbo.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gttjxghzvb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtigahydfe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtnuzvxpin.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gtxhvkuevg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtqzkhynmx.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtxitienzz.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtodpirvhc.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gteiwxlghs.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtrvqbshtl.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtbgdvmijl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtpvjusuuh.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtwpaqosoi.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtmtwbigtg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtwyavcqbi.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtsvugfgye.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gttfyqjffd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gttxbzmrux.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtxygoxtjj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtrpawtqtx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtduyubysp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtueiqqylm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gtumjilajw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtelihhwtl.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtnspzfysg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtrqdmbqle.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gteeasawbp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gthzambxdv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtdlmazusr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtucktdgpa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtxcnqdizo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtwioakstd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gthlztlqsh.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtixledgzh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtrlfazlim.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtzqzbcxkc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gthdemazlm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtamfgijiy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtoigwpdew.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvleltpyf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtwsxcnauw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtaznmmcuz.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtpseedonl.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtekepbgcs.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtsfttntgo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtpokwfkmt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtoomlzpnm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtwmxczizh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtnkrvgbrz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtttaihgrx.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtytkxiruk.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtmtgbyvxt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gttrbowprp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtztuthuob.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtnrelrlwi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtrddyzxio.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gthisrvojn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtdxaekuzy.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gtllogaiie.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtmyvgqkwr.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtnkqqglbu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtysllzrrq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtvljoyjht.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjanqhsmk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtzmtfubdi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtiyrpvzki.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtxqlcekpt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gtritbnerk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtrepxzktl.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtvrbtjupv.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtnvdokppl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtwqyxopbt.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtggehsnnt.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtymtmsfbq.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtjmajlozz.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gtccljaovw.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtgnknpcot.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtfayhgten.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtdigdiivd.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtuctobyzq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtxsomhhqg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtpuohgmzz.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlffyqfe.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtlbowzukt.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtmkiyhrhy.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtmarblxqi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtgorzmivk.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtxbjirkje.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtkleuofaa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtnzmdvqwb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtjpcbmmem.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtfgbskwzv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsdwoynf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtumsugqnd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gttulnrzrs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtrmmocscg.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtrvqhfrvj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtrvrsaifo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqgixjyp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gthcnwxdjx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtpysflwyc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmpqkgpc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtyfhubvjf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gtrnamsmjz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtwvzdshin.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidodfcfc.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtljpodnlz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoygubvez.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gtvkyezqxl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtrvuangdr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdxecelw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtijszggap.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtyidsqoda.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtatvrggdj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gthpvubmbh.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrnriggh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtnntlgyno.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtigytvjxw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtiyqfxklk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtisjnhfnt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqblnqzgz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtnimxaoty.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtmkaqemet.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtyszesacl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtzudwqaqw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtkssgsyde.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtkknkhhed.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjazjvsj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gttoigzsur.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtaexyfijl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtingjobev.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gthdyzyedf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtynizqbwt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtletivlyo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtaulbookp.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtgzeloywn.html


<!-- 参考信息 -->