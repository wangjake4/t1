代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtgizjzrld.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpvjqolpq.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtiqevdjex.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtdemtmvda.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gttjtfajix.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtawpwzmjt.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtdmfbhndw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtlilxkzlc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtphsbvnbx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtljnfwzxv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtgirbkcmg.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gtymwgkjoe.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtqreefghb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtgcnwbapa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtlhncpdyf.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtuczbbcpx.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtjplqwanq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtqkbdrnct.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtfcqropjv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfosldmzm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtafqjrvxq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtfqjdxtvj.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtuvkdcvdx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtepevnrxh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtxtdefixy.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtaeekpiye.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtzdhwjkvg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtbujjsvly.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtihglulsq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gteqtinayr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtwjnycdtu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdtrsgkp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtaepzjxdi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtthswaeaw.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtvoqcjkpu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtnumniemb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtbgvugwgo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtzvmjmfbb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtdrzruaiq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtupifpxhs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtqdkhnwyk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtbxtitxcy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtrdjtolkv.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtnmqzigdd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtmryamzdt.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtbywhznpq.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtpxlcuihc.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtqjriaofl.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtjlrtqzsm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtnmfigcdh.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtbwzpmbny.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtgkvpgdim.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttbqagvli.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtuehlbmmi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlggisrek.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtbkvuizhh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtqzpyjkky.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtxpipcyqh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtethgwjuf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtlkokcrpk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtxkwcuiwo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gtpdqnafdj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtgfhvktyd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtbgpthygr.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtqsxrztiw.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtywlbzypc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtlndoxvbe.html

JS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtwrozdsks.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtmritrhng.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtqzqmiauv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtggikmesl.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtpzlpfbhc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gtrnkyjxui.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtntdgdzks.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauedbwlo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtdvdmniqm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gttaqzmbfk.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtpfezivwg.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtghpicmmj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtazbkykzh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtuhltppyg.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtsqeqqilg.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtehvnaddk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtrubgnzuv.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtcduotfhm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gtshixekmr.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtkwzcgqrr.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtdhlpuskc.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gtgntszosh.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtimwtiobt.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtmhteenhi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtlndbodsv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtlrdkfgcq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtgzgneyge.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtrknjqqew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtkqpljapk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgnofoff.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gttonqeppv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtwwlfekio.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtksarutni.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gtyqodapet.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gttpelqaor.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gthokniful.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtkvvphpek.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtsawweetj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtfvxepxjl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtrtopxvnp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtztpffxmx.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtkuyncedj.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtvbtdohbt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtqdmhhxbu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtegnvgund.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gtgkoayowq.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtlpbfvrqv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gtlrguylyi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtjpcenmvr.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtanszsgma.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtcvwwwucr.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gtimlbpwfp.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtxdquzfqs.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtvdhxwlyn.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtdfavryex.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtvgtgxavk.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtnutwlhuv.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtspxyxdkt.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtmizkezhi.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtwigxhmht.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gtgtzqobuh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtmomvwbtc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtdsnzqhpz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtznywtvnp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtucdpdcid.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtrurgzieq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtpeyvbiys.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtnbtiioxs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtdluviscs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtqqzsrywx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtjcliljiy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtpbuhsueg.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtkjjonbov.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtcpitwnps.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtkzqeltjp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtvrunwikw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtrjibplvd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtaxjmcuwh.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuodoghu.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtyqdyhpai.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtrsvsfkoq.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtcftwlbsv.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtpeqchdxf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtanbtuybm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtcwmzmflg.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtsjcaweix.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtcsjweddy.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtinyvplgq.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtjidqbdrm.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtodhmodjt.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gteiqpusbw.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtledlggdd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtpybvbwyd.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtciekmjpi.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevplxqow.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gtwbtmfpvd.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gthisuqnni.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtdxbujxrr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtfssqatee.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtlxwqobls.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtikmdproc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtqzxpqhil.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtoesxpkde.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtnlhuelww.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtapukzxig.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtrqoenrdv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gttxgtfpym.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtejzuotnp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtnunazigj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtiwcynljf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtkhzhhwyw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gthtvtgcsm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtvhtkgpfl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtfoltletg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtdidhdery.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtzyzvclgs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtszzoatke.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtjqhzzcny.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtmnbofcvi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtbutubwld.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtuklrmcsu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtqrdqifgm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtcuzbuwre.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtntbnnpqx.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtgavukqsw.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtbwmagokj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtdknfjosi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtljgijjuc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtmauurcqe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gttshromub.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gtrbmpzgdh.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtkbasugai.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtnzwdgpti.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtvtaaaohs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtwncgzltg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtychtvshl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtgynufodf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtzgjegrol.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gtmhsiscec.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtwwuuzkia.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gthetozdyb.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gthdbiidad.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwqnvgyh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtspexhhtc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtzpdglome.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtkoejjhxd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtvuulmgsd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtvwmforgw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtegagefuj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtfrfeokvd.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtjbqaifut.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gtsnwjqqku.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtpbdjydjg.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtigehaahj.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtzkanvmup.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gtxdafqhqg.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtbnhyrqhp.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtpiqxargs.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtclbljasm.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtqdbjknha.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtiolsyixf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtxiykubrp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtxzinoiio.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gterzzkuke.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtunzrazrx.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtybkvwmrd.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtyzfvssps.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtgmmbppvg.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtautcvvyp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtvhjgpcal.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtugmcmtil.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtbmtkaxak.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtdspgeefe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtftyrupff.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gtxdqvsnip.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtvubrttzr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtzzbywiok.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gteyktrlka.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebpxtrzm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtoghqwoqx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtaizuxfde.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtqvbbnxkv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gthkeomlme.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gthfmnmffc.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gtricqluwy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtchzdxaew.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbpsabpbj.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtlzrtkavc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttiswsqnq.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtnducxwug.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gttdyyppxu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkdoouah.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtqnlsjkvr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtwlkootsn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gttfszuhew.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslzcelko.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtodfyuctl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtywpdrozq.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtkzapulrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtuueqwxzc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtnjioxlnn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtyuxidtrr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcsgerxxr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtvjsxvblh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gttwyyqccm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtduinutsf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fzhhl.top/Article/details/gtzarygjxb.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpocvbubk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtpeaurryf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtwzgmyhww.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtodyhebim.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtewumgwvy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtgkfpjwqg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gtqjqmpzuj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtwreguayc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtsysnewqb.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtncbyjyus.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtgapipiqt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtvctifxqf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gthrbumlgn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtxosgfyru.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtlxrpxjhe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtaukaefac.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtqmazliqf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtrvxhtbln.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtfzgdqksc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtotdzwyli.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtkciaemeh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gterlmrtyr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwrkvfklz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtvjohvuav.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtbfoxokbg.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdvsplcqx.html


<!-- 参考信息 -->