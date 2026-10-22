代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvbqosoo.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2bryhypsi.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2tmhexpny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhhyorro.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2ysmgkbfn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2jrkmkhff.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2oyrxvniu.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2rxmexktu.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2amppbqof.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2qldkfgla.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gt2robahcne.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gt2trcoaihr.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gt2vbifjhwl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2jydwlepg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gt2jecbyfbo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gt2rgaoxadq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2rqfzlyui.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gt2owfvyklv.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gt2usqlkkje.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gt2aivitgxo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gt2xcvaaqcf.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2nwgliyul.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2jwynpens.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gt2rtpenakk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gt2ksccvzwi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2zqszobuc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gt2sgekbykg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gt2mzvmtqws.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xphqfabg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gt2guymamaf.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2foupbyst.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2uayvwwsw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gt2kkbkdkzv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gt2gdmksfgo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2haazldzt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2petpwuzj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2dlhwrkvh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2wpqgmdte.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2cocsktsb.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gt2clmzstls.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gt2qxqoshdh.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbstqyox.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2qmckunvr.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsnghydb.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2eroujaiv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2odzruidl.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2vlnlzryu.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2bckuvcbm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qigvhksc.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gt2smdopqoh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yteukkbm.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2ubjctrew.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gt2aurqayve.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gt2iiljdsil.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gt2eyiqwjri.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2lokmzzoe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gt2khankcul.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.smart0.xyz/Article/details/gt2zlawzezd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2pymoocma.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2ahrdazbc.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saylnxag.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzfbwhia.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2joqflvaj.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2fgkbixgy.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2ornslbes.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhoyimol.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2meapwybq.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gt2jqfjgxcf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gt2pmjowwbh.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2gyzwzxik.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gt2ycsswenq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxclhinq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2cclstrjo.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2ukhltosp.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2esgnwcpv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2fjlfyjpe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gt2gbhvqeve.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtmaltdb.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2lvounxvq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2dblacecm.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gt2xrektnfw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2epiowbsn.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2wdoizoil.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2iwdsizqn.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2vlyovhck.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2ddnisvsh.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrdylatn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gt2spxakxbb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayvmxtdy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gt2vqlrsrbv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2jbjzbzyz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gt2abyhlixy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2kkqmbpcg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gt2dcfvtezg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gt2csaxyohs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2xphpyylx.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gt2rnyysfbu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2ozwdyrzz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gt2wrjgacsb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2tfmaycmz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2ykmxiqct.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2uoxijjec.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2hsqhmqgk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2kvvcdugg.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2czoilquy.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2poauxymn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gt2xnokqzcy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gt2ohqhdowr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2prrdtivu.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gt2kfpmqoek.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gt2vsamrevw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ecpjivaa.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gt2vggpvksc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2xrktsmzq.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gt2vzrmlpea.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2qiktqtqu.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2rhozfgmd.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2rwczsaur.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2iirpoqfd.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2hjipcerp.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gt2rhjegvha.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2jtrunsgs.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2fyfncdqo.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gt2vupmwclj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2gvcwsmub.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gt2cxwbgbrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2odpcyskk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2teowuicf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2tfaugisq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2hbwlbofe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gt2abzowtzw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2noaymswy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gt2plixaxls.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2hdvfjdsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gt2hysmjpan.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2tpvowlnr.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2hpgqzmsa.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2bnxudokr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2ffyavhqq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2rmoefefi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gt2neponsby.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2yhzfexrj.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gt2jvmstxcy.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gt2dhenkcpz.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtmmjeqw.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2mljaubnp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2aaagetxg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2fzbgjeig.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gt2abzebjow.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ustnuyzw.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gt2hjfkbvkb.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2bipmkyrd.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gt2njvkzehj.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2ksefukwr.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2tbkfpdqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gt2hktmwxjh.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gt2viltlekj.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2pidwyguy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gt2xpeofgjd.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gt2jebxipcw.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gt2earpktit.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gt2nstscjhn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2hwpdsvjg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcrngeyb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zrvwpkzw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2flnmtcmt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gt2svbubutr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gt2zvnfwsoi.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gt2emwfbnpp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gt2oswvgkzh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2krssulyg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gt2mzfqzhkn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2ywsgamhj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrfcphxd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2rofyblpt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqllapqt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bploqoyr.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gt2tnsvqwnm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2fktiyrug.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayhrwhqh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2vpgbtynp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2tbyjnmkf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gt2fvobrxrf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2fysezoii.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gt2xrlgblhq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2xvsmpoko.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2srlsixng.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gt2pxjyckvq.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2saocldei.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2pxyzbytl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2hlhgjoaw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2zhfxmtic.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gt2rbzgnzos.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gt2lpeiedir.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyogskoq.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2tglxwtvr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gt2lmvpbzio.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gt2akzshjht.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2gqhmpwws.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuksbmen.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gt2eavctkkt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gt2odrrydam.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gt2fxaymyyj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gt2ysllkcld.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2glonweib.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gt2jitoblbm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gt2zskwavdh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2xsrrkxsb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2wdkosquu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2fpoufecu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2vsxkishd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gt2udyzgwol.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2lehsjxiq.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2dlmwfmeo.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gt2xmcpzyln.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2qkbvqibh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2wlwsbsvh.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2kqbfuhgj.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2gtdxntiq.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gt2tiphivxo.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajbkclzq.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvabtxpg.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gt2ctvbmkie.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gt2dlbhgiij.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2xywdmwwf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxzqtkum.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqfnuckc.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tvbtbsar.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gt2vtuujhpz.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2kviaipow.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gt2mhubhjcg.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2jneoxmet.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gt2vctwqacu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2quptcfer.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2pgwuyxvq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2ejdkzntg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2xpjobovi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2skpqpgqy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2lfrafgzf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2vxtmleip.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbnjsest.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gt2ebqxrkty.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2dwaezkeu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2auoxxptd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2teajngen.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2vovdbndh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2razmekgu.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2hlcrqxra.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2ehxpbdle.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2zockrqke.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gt2hhbuxyxd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2gndlevne.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzysfvzn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmbvvicd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2guptwcxg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2zmfioqvt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2ertqfwhi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2mwogaqey.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gt2cwvimxms.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2rglhyzgd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2rwkjjnyv.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gt2ubidjdcp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gt2dzigrpli.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xouxpawb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gimemrpf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jywcvfnr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2yrtnuelh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gt2xyowipzu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gt2gwsdbxmp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gt2cuwzexcb.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvwyjrtg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2lyhfxmpr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvnwwedf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2kwevttoi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2rmnuimlk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gt2owhyvphf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gt2upsmoagv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdxxhdgw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gt2qusqbgfr.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2vbynbkuf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2bcjrcxuu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2ozdnuypd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2eevencrx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2egoqnbuk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2rohsfgkj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2ssckhfhu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2krbofxdk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gt2uxpxgpqa.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2oezejhzi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2mmasqpfh.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2utydecza.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2iyomgenf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ejeycjdo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2nvulsoxn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gt2rqqbitkh.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2xmqchylx.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2yhhuuevn.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gt2vmrfmmva.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2etmhzhft.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2sdoerwdp.html


<!-- 参考信息 -->