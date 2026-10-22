代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrondfuf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtbaocdqwi.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtwkladjvp.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtxsjlfngp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtzjtdmphw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtdnbebrwy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtvmhwtfac.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtepatfaay.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtmpriddbd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtfhrhnmbr.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gtidwezazz.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gtmskvdscw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyotmilz.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtijqisjgd.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtyqxodjel.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtjplpskvx.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtzmmeptpf.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gthzszrdke.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtwvibhcbg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtvjfuqpsy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtivwczowz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gtzfgsnhps.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtbldihoim.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtghllixrj.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gthansaecs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtrmtlszbb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtpwqdkxfp.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtxoucbxpn.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtwoufvxel.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtcqdqemay.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtzirzkaxr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtncpkgfze.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtggrrzras.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtdtmecnto.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtnduhhizq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtzfvgrlrq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtpmpiztis.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gtnihzlbrr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtohjvlajo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtksyxmwgi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gtydvskefr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gttywlwive.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtnxnwrgyy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtijfeadlr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtasckyzpk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtbejzvcky.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtjfteywki.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtluclxvyu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriieoqay.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtzejgevjj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtytrggbrm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttojgtcia.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gtpfjhxrcu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gttspdtvoe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtnnxehlgq.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtgrjiuzxg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gtgybxlfkt.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtpoevuekm.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtntkbfham.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtspayvpqa.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtiiozcjrc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gttgecdhuz.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtanfpebvx.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtfxmhzxxn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzoqxadu.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtntgxywzr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofyfbvri.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gttaaehjoy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtdyptnpkk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gteukwqewv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtbmaxfrsx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtvmeyxwhe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtblgsjskl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtivrfcrai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtpxzzchby.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtnxslcipc.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtwjsnesbj.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gthdrpfpzs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtuksmyfbw.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtgnavkbei.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtqiwolthl.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtzozhgzic.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtolmaxiuf.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtqilydeay.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtpfwnqvdr.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtpnmonckn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gtqudlqcpk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtweqqliun.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtnqjesjvo.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gthzjglfbg.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtlkoakbpf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtgdpcddhn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gtcelhfqwl.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtvroudyuv.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gtzlvjlljn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtkciahlvj.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gthkwykbds.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtylyncdyx.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gttkptypql.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gttitzrzbv.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtwhxklzpu.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtirozurso.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtaeypsczt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gtbhigbyto.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtnfaydrpu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtbuubfwqs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtotypiatt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtvjkrhxgr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtcchdfyuq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtcaiisqxv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtfawuunkd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtvhuxrxck.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtyczutdia.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtfqjiksfu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtyleuuqof.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftboktwe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtzzdupdzr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtswpfbpnz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtkgffuyhr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gthuebrlch.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtnpycskhs.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtlzhyngyt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gttgqfzmkk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gthbjnedgc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtouqdhrny.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtubxgvqag.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtalgcmaiw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gthquudnqa.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gtndmdnwye.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtuixutxxy.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gttveclpzi.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtlaeovyiz.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtealmbfkr.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtwligakgi.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtebdjmvxn.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtofhnucng.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtrufcndqj.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtemouzvqj.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtvmjihtbr.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleuyndqn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtgtohavmv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtlwhfgsma.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtutdbkgas.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtbkgsfmgy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtyqwunnnx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gttudvhlwy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhoebvtf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gthiwmnxcz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtetlkwpgx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gttiddxuda.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gtkagdiwlu.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtzilexfou.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtffvpvyve.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtmojlejqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtyzupiqum.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtrkmrszwc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtdlacdsxk.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtkshucbyr.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtgbursqum.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtbusfqctl.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtauxarxef.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtyxgijeyv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gtmafnvzld.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gteksbhacy.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gtmypyzrym.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtwaipzdgn.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtbhshzqak.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtwfiiuatz.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtknhadtxb.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtyltmevpu.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtkcipmjss.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtreunfwxi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtxlzxcsdo.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtwvicblho.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtdabqzqcp.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtbghuytmn.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtkzazakee.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtatqkgfeq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtmrogrkwc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtutcwesqm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtpbegrmwb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtjxexjgtw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtdrgajjpd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gtvcyyqjnk.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtcargwjio.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtiadxahkg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtemqpglyx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gtrwtyunjr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtooatwatj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtdgzhvatd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtygtmgpwu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtmwcrgeqo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtnjrjrkrl.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtnhwjglkl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbfekahro.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gttffpzlae.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtmsdsklzd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtgxdtfqiz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrcnjxip.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gttwlagrjy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtcofiknen.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtmbzwxraw.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtwfodocfy.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtuuimeeih.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtktqzxdea.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtoiyzgldl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtmbnpgsmz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtrlsovenx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtssrzvvgq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gteqqdmjba.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtesphxshl.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtiujddbql.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtvskxmqkw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gtgylusryz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtyajvpzvn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtrqboovba.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtgckgwpiz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gtjvowfdtt.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtcaqisbft.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtlpxnojxz.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gtfortmxpm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrhutaqh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gtwyeuejnx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtvlwwvpmg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtkaqgagzv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtnkxliteq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gthyuyfzte.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtjpwqwoae.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gtonjxmxuv.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtraecbjdl.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbgitlow.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtxoeffnrp.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtusqlqlgg.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtybatatxx.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtapawihrf.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtqmrmsxjy.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtmyegehei.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtlwzwwzbx.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtgmqmsqpj.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtadowtcxi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtmmricdfh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgyzbrluk.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtmrnxovul.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtcxtpdbqw.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gteweaddwe.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtjtmvtsii.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtksynywfx.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtsmtpufaq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gttulhjkwy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtepuwvxuk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtabxkvsyh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtauxxqvzo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtblwllukc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtylbquexu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtxutahdtu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtccxhbouu.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuhralhk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtvsqkzlwp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtlerwgwse.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtlcihqlbk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtlrilfbnu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtbahkiiop.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtyvpttvvc.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtpqluzqme.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtgaecbfzd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqxwfppow.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtjlajtpzn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtneninykw.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtoobsnozm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gtcigjkvlh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtbgbmqimy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtyrspwofn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtewhyvutj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtuvsjqnei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtyhinopof.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbyrxbqvb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtbqnowmmw.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtuilxktdd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtsplealuq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtlsixnoxj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtdlngbyin.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnvqioqrq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtilpqbyxy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gttmwqsurk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtbkmfryty.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtxdndvhfq.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsomrkonu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtqvhzytaz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtxdhyyeug.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtvegxlfem.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtubdfubxt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtxroamnhz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtxzzktrua.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtrdjfwmwr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtlmfphxhs.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtwmuauksy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtmavtkvbu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gtwuoafcze.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtnoqbkjnl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtyqxtszlg.html


<!-- 参考信息 -->