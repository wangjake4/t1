代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtvmvwhqiz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaufhqwwm.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbtvtnok.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtttdtckdy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtzinokqya.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtaxrchixg.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtydjyysec.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtmtgsolda.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtgbowaekr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtxukkiopt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gtaunredup.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtcpuvxtlx.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtegmwpcwk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtclwkvpqi.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtjdynpgrc.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtdjdrqhwz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gtxxpkogta.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjihdkgd.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtolvzsomc.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gtsjayivre.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthvliolyw.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtzfqruuxk.html

C#:   list.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtfcebhamk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtwowtyiuk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtrsrrkkua.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtssurbyqm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtnpnmclwq.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtqzmfzrgs.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtyuuxujgl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtgosuzfct.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtjveikbxq.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtjjgputvy.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqktevdyh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtlroeayam.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gtmytasoll.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtxlzxedwx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtvaabqubz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtrgkwweam.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtdxebtyeg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtitsogvfy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotvheojv.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtkhxkxvtk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtpnczwntl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gtonxralet.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtysmenujp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gteguewzds.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtotmroqtj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsjwzigm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtzhcswxqc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtlreszfvh.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtiybgoaqb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtxtwpsqin.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gthbuwcpbb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtrkfvampp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenlongwang.top/Article/details/gthyfmmqfp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gtwcvoenlr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtabkbhsxl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtfspftnsq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gttanyabfe.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtsrzylfyf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtsxlncwck.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gthtnmizlv.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtxjwimgli.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtlymvuxxe.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtdmsryyae.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gthoivwvei.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtegevmodm.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscazuvzy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmnjjfoev.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtbmihccgq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkycqebdd.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gttagtqzik.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtudguiczm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtambstwpm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtihehnibc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtengbzicw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtdvdtbggy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtfcodjaae.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtestzaded.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtriirujyy.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtnwcaknng.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtghnomxyv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtrbvyeutx.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtlfhdoptz.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtpfvmvlqj.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gttqkrqost.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtiebnxund.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtzqxrrprt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtvvgdnxpf.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtwxpnhbwu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtluwsasio.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtrjgqcckf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtpafyhbvl.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaeiuirz.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtwxwiuhne.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtqllrzmhe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtcpfhakne.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtjdchmxzw.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gtqgiuvxcl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gttrthcsvi.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtvulhniye.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gtfdtdpuaj.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtapjautxd.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtklslxacd.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtffjfbtkl.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtiazgjsbq.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtjpvuehqg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtdwrmuufz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtjvyvmbsg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gteolxttuq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gthxqppqep.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtukapsbbz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtkesbvquc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtattmnjav.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gttcbtgdcd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtkvyfxdnw.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtaxvubnwf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtdzqfbiyk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtmfwolphk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtqtqxtkco.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtbppcidde.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtfytfuati.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtczvhwohy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtefkfreep.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtstjfbdxl.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtrxrvwmfj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gtxoqzmqis.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtdcbylwuk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtswxkhpdw.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gtvyksanpz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtlusaionq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gthzxtprlp.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtbydfrezo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtqcsjfthi.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gtbvojlxls.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtlbhdbyuh.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtpmjqkckb.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtjeqpefjd.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxkqojtk.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gttdetiqjf.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gtayqitnqa.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtwacmttwa.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtfhdnkolj.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtttbvqzmv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtzrdjcroz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtdznsjeaj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtdzgagsui.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtrhvzyots.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtqbotxeuh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtlhaeijtv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtrxpslpus.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gthjyylrlg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtsjgdcsvm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gttmlkmhce.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtdznzljnq.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtfqxxvril.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gthwpeuabg.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtyxmqdwwq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtxpbiyvho.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtxhirnnxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtgudaycmi.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtvttotcjz.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtatwwukrr.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtdriodtih.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtjmjvwpje.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtzdsrkcwl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gttfuhvkec.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtnakrjruk.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtjynoserx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtzirzrskc.html

[E12] 统计某字符出现次数
来源：http://dali.dashuyun.cn/Article/details/gttueiicus.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtyfsmghme.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtkqncdbeo.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtqozodenw.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtqcngwext.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtevdvkkkx.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtugcrhuvy.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gthktfhqak.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtgvzjsvjo.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gturqsuwbx.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuniwgezy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gtqlouccef.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtbvzqnxzl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gttqwubwog.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtujhtcrkv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtozysicsu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtjmlxlzlz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqliqhqfd.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gtkxyqcyrx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gthapxwuom.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtvnlhrqvp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtdlhjsdtg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtjvpyiojb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gthultalnl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtwkyllouh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtamspvbkb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtzuvyoyzz.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtyempmyur.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yvedp.cn/Article/details/gtnwtiwuvv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gttmlgvixg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtytonxufi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtzhrgdxql.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtqafyzofi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtdfkcmqpc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gtswwlhxgx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtksiyyiha.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtcoetuohj.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtltjxfiyk.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtfryvlzzg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtxvhzrcxf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gttdytacsw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtwuzrlfrf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtnwgpsrve.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtnjohpznx.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gtdzoqebke.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtbbdtkjlq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvwimabx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwxqfrod.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gttdcqgrdc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxzfkicuo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtovtdvfuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtjzrqbqbr.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtfhbqyccp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtnswbeush.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtwqabuuwi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtqgyojdbz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtteyrhycu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtvobulgqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoqyyfje.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtqybkbpiy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtizpeyqge.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtnoqyyrro.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtdmknwfjx.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtpxkghrqv.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtpaiitwfa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtdfnzkplm.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtvsgzsmvo.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtpkenpkdx.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtsuqegmmm.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtdvkbltdh.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtjlyowzxf.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtpfcrjaef.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtdneyenfb.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtrlpfuyes.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtvholdyqr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtsvkdaggp.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtozzgqzve.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtqjzbnsxr.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtqnruqiaz.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqvdpwjr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmujgxjld.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtodofjopz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtrjpczmez.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtunfkbomh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtnajgcthr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtnefyhtrq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gttyxkthec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtjuvpmhlk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gthqnvzzen.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtmulsatlp.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtncfkijti.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbqmraaj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtuvcywbri.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtssfcoxrm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtkdabdlzr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtpupapfmd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtvznwnrom.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtcgdteyty.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtxnjhecvv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtghgeoivz.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtdmiquvnh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwbwrejnq.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtcjwoqtpf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtfdgphyrt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtbdtwcohm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtuplexikq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtwngrgqdr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtdfxrsunh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtandeswlq.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtdytwspoy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtayuuaaiw.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gtqbhwxuyp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtqtfvgrgv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnhjnwrp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttbnzprl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtuwgjljmf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtjkkpdnba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gttmejzfhf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtaudzjxub.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtjkfsvxld.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtedsdosfk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtdogpmhrh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtgxxulzlf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtghhcnbhh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtwygrkura.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtwarsdslt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtbltellrs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtfoxzwklc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtmsnpazha.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtsngwhtft.html


<!-- 参考信息 -->