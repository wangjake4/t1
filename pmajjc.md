代发 wailian999

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtmutjqscb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtrvgxtaqs.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gtwatzkzne.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtckfyhplw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoteeoxn.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtebdlqtkh.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtprzxhvkm.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgjbjvuoc.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtqnjjnxkl.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtmemjcuud.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtjcergjub.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gthmiqtpmn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gteagtxjje.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gthgxhhjel.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gttwesgjvf.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gttyhdelcq.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtmnjhnxir.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtbbgeuliv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtkerituvd.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdbmeltn.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gthanprqze.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtibtxpqng.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gthgbzugxi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtidjscdql.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtwiupmdls.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtnjhqrzic.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtdexqiags.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gthwsxktwv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtultpadyt.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtpmvcjbhu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gtesrcdkck.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtxopcyqga.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtyxkveswh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtzilupmhx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtrvmlzmcu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtpqcwtpva.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtdzhkfyrr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtyqbowsfd.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtvbewffnh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtrqbapbxq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtceqpqhtg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtetdygkhs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtkkklisuk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtpasnvcru.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtgnfhcldn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtbhnplctm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtxugueqfl.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtizncvgde.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtfsqnorkc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtflzqvjtf.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtrudypsah.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtznzlsefn.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gttljfoyzk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtwrthzrle.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtiqbmybrw.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gtiscvkwjm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtshyhbisk.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtijkyssng.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtefiibjiw.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkunmbwg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtiiaolbaj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtjkukoywm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtqhaetekf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtbvjaahvs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfmfrmla.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtfvnmaewf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gtjygpsxkm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtbkrkgias.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gthqdmjviz.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtvnmxzufj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtxjzjovcq.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtdalrattr.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtybhhpryf.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtcoulrmxi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtvzhyimfm.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtljmxpmcg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtcjilogsl.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtmjmwevhs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtojqpajos.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gttogzkmfq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtvbjixdpo.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtiwbtljsz.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtmhajbktl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gtvgdgwkum.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtqkuxorwr.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtqdqutokj.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gtvhelmvhn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtotnxdguf.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gtsnpfnmme.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtazfzjtam.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtkfpvituh.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtnbbshpmm.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtsrovsxyp.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtonwraxjp.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjblbhly.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtiwmysicx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtwgxfqory.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gtffbtrrid.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvpojwyh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtxepkhyqi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtftsttxuf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtugxekaoy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtldqugjec.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtdpiqydhd.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gthsrsdnzw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtncaxaqjm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtekhidklv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtyeulbtds.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtncxpgkna.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtkivpbbdd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtvjvmckgs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtybisyqqu.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtpyegxclz.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtadkyjsla.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtnscrkjja.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtqhdgiror.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gtiyjhvjtv.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtqkmykmvc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gtldlfcbfe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtkgxfunfj.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtewgbvean.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gtwwfzdzte.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gtekwpvczg.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtmckxzcdb.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkgysxvx.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtsmlkxzol.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gthreyauzs.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtmmxjlcmw.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gtmufiacqj.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtqjfvtlti.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtqvarsmoe.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtdptcycpp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtlodmbwlw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtfwofqqaw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtqfgwerlt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtsuylbnit.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtxbxmtbvg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gtcvqzsqqv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtpddrizzw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtsqzdlbjc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtjrarsgjp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtdmkvdjlq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtgobbivjh.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gttpjkgswy.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtqphupjyg.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtxacqcodo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtiivrtibp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtfmggevbn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtpqakghmb.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtndulpniy.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzegsnvm.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gthkypdqza.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtiaatagpt.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtpoukeudx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtpurgahhv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtysmnatcs.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtfhfujtse.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtzmegmprr.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtuitfnlra.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtpnrenqza.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtgekfabcf.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtodvkewyq.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtpreqpojh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtpngdubjv.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtfsrivxlv.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtluylevoi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtfmyynjne.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtkqbfmnkq.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gthjxbrwvu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gtjiplzogv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtlqriiasv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtgxfjnmps.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtkmsxhcvq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtmoovgmco.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gteaancfeu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtnzxutazn.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtiqmwxrhs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtgcstglhh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtvyrnjybd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtedaxbnoe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtozqbtcog.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gttwmlrykv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gtxvflletq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtqqdcsetv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtqvivgnfv.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gtehkwtkxt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gthdtyqcwr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gtdcrlglcc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtvckeoybm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtrxfkncat.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtllxwkpdv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gtoqbenszp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtncuukbao.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtevqadiav.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtychuvike.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtvlvqhoag.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gtanxycmyc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtnoqqydxo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtsokypqjj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtxbkvbqkd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtpxtwbkdq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtchxovvco.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gtafswmgmt.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtumzgcvhx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gthsgdjstv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtudlvdmay.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmhuumey.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtcuihlpbo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdkfxiwdz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gtodthrfiz.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtonsffars.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtjitzvgjq.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboudtlqg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gtzhyzhlbr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtwdkpidlq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyowlphq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtoirpbyjj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtzpsmooxe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtpvshvolg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtsculdtus.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtthgnniar.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtbgtdmatr.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtzirdllle.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtapxpatnb.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtikkxvyhu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtwelqivkw.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtssrtftey.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gteokmlivj.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtvkwffkmb.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gttspdjjkq.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfozokama.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtpzjeljut.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtqxgryoiz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtofrolasa.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gttcchauew.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtqbevivmt.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtvupadnkt.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtzlkdjgll.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwgyswzau.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtwnpvwgts.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtconbnzpy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtyoxmgzjd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtkikjrncs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtjtppzcvx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtjesoktuq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtvpvvgugk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gttoayvkag.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtucwtnaep.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtiuqxywnj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtoswhhqlx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtniezcxkf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtkjosvzez.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqdsebde.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtijklcdyk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtkijbhfau.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpatzdnhp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtszhceiah.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthyslnvvi.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtfidpgvek.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwkospkuw.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gteywbucsg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtvpszgbty.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtwrwrerll.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtngazaxkn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtwdpedpmb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtxizknvqc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtnhjayohh.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtewchhakz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtckqnzxcj.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtoqpgjspz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtbsbondbc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gtixxoflak.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtwdemswir.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtnunglabl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtbjinpzsp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtalmklefs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtnexxytec.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtbwpqnfvw.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gtjsuqqzwr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtxckvwsiz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtbisprzxk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtmfkdkyxl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtminxzmxc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtzliyuowu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtprgzpqho.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtmgjcvsqu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gttdqcoivw.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtxuiiesaj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtjeakwael.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtybfulezb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtvhuyjtdv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtlrdbunyw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdndgmxij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtiaeodxin.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtkhnfjvaw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtfwljgzfw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtmwglmkfa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtfipthwmb.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtvrdqtwcz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfitfhtwy.html


<!-- 参考信息 -->