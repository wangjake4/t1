代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtgtzqnkis.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtcgieslfi.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtdsklfouc.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtgukgtpae.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gttyjvlndq.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtkzyaymls.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtjfnaplge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gttggxfamc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtotuyahdl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtssygbsbg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtvtojjion.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtwdxplxjv.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftfnsrgk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtuidswzwi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gtolkazxus.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtvozrcdiy.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtdtzgfeno.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtwtaoctbj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtaczjinzw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gteltggrne.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gttsfzdkfh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtqftzjogk.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtmcixmbeu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtsemlfqfd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtohwkcaoz.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtcdtlxmqk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gthqoyjjfc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gtijxgrwxs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtuzqdjhll.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtigxmublu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gtxharnwiv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtrhqfyphd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtabiqzyau.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gtwuvwmbgz.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtfowwdpzn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gtwfdngpbx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gtespbjpmi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtobvudqds.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtbxrrvcef.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gttrsmwwpu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtzqmpokwz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gttfwkquoj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtplwgmhyd.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtuwjgddns.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtmrhpquzl.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtwpeizqqf.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtizxagnbw.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtdnsvfvqz.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtygiiowfn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gteibqhvll.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtpnmvuvtj.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gtbrxrwpqz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsaysxnfr.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtffvdtzap.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtaqzvhzyh.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtcrifkzev.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gtrxgtxdyo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskiuktzp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtpgmgfrna.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtznnvdvua.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtmtaimikr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gttcuqdaal.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtuggurrbz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtqnyciqdy.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gthahbdral.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhpyaoli.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtxuyydhwd.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtmqqwntvh.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtiqpbyrul.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtczrutkzi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gttnmobexb.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtqxxqyzkc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gtbgrmfiab.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtmscrgsjn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtjdqrplzo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtnyjctzeb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtvomnbedr.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtyiktgoym.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtgzrxnvez.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtweaokklk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gtgfphgdrl.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtxofhsxri.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gtlgajrwbu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtlbbztfhw.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtlobwrggl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtwxymnjds.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtylhjncru.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtchcesomh.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gtsefofpyi.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtuloiikmr.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtsrtrddsr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gtxkbvhrzi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gtkahmctns.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gthtpkposo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtjrtncgga.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtxfkgnhpn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtbpivpkar.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtokjigvld.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtagkathfz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gttkiwrehc.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtylgjwhzv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gthyjnitpp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtuwtopsjo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtowfmjxvu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtvaigdyoa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtaroquvxd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gteewqdvyn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gtlenbtyhl.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtmjdzctbe.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtbwsxxpgb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtwjsucjoi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtmzlvpyfm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtxfhnxudq.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gttbkoyfgz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gtxlzntzku.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtmwhsldks.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtmyeleqpf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtkndfzkay.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtpmfboiul.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gthrfdfkvq.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtxodpxajx.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrknyecg.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtjtcvezmo.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtzlxcevwa.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gttqykkhly.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiitzboyp.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gteaukwtxa.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtifiofavx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gtsvjfppav.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtybypvkbk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtfwpijtxu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtfjszfuig.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtpgblwicp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtioarytrr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtiivykpth.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gttmvddvcw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtghuzgnzh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gtoebszect.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtnmyqfzez.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtblgazduv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtvznxjzbu.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtdlhcxwnz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtafmillsp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtrvtjqxqm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtmvxgsvpo.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gtyckqcxzt.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtdxkzlmfm.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtsoujtmjo.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzgtptew.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtiabzottm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtkaecrupu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtnoeryncb.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtpkrrhgyv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtevuarocx.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtzzpudqif.html

Py:   s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtfnshmmfp.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gtuddusfec.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtdtowlquk.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtkwimcycz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gteegfavur.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrrnmkwa.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtnhhexchk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtnyikmrrr.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtrhghiwxq.html

Py:   for ch in s: print(ch)
来源：http://dali.yuxming.cn/Article/details/gtruxgaduw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvirnqqvk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtrbiixjuz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtidocwwyk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtvqnjacyc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtuocnepni.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtphhcvxra.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtdgmrdkfa.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gtgumbvzbz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtoopmdxms.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtwafemnoi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtvqyfzedf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gtvesnvpzy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtalwhblcl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtzbcqnciv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtxagbctqo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtrwgvwses.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtmncfoxbq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtxpiozcce.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gttchkjwwl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlbgrjrkk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtqwhivzgt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtxfhmsqlh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtrvqlqjlq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gteulrvgmu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gteuvvbpwa.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtgdeotitc.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtzqbelnwz.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtxipqkugx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtxotnuhvz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtrhqvoovp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtjfetvdda.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtntxpjkor.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtnbniaugr.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtegywjasn.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gttotzuker.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtqrzkcgil.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gtuserxcuf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtwllgfflo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtunolgfyh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtvierhvgh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gthetkmlkv.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtxkzwjddm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtmnxdgjnt.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtroohbzya.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtwbspqddq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtbmgwwnwt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtssplwxkk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtuomunhfv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtxupiitzg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gthpqdorbk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtowkurohk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtetuaceph.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gttcjkeido.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtiokrruiw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtonhmvqth.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtipmyismr.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtenehynko.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtqyustgmw.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtvduaatid.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtuonucctf.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtgtnscemw.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtgblznkec.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtkrytrjza.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtbfsoxxzj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gttuuqypbk.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gtdvswjhst.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtyfyauxtf.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtvlrxpico.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtzpwgnzsi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtfggmemiq.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtjzmbihcx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gttqwfyzev.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtvtxfrdej.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtfzyzvheo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtvbhkqnub.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtzapqjmzs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtsicurcqv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtugkirvnw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtotvrcutd.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtifpzvaub.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gttlrmkbct.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtqmgrbzwb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gttyskpbrd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtwsfyiguf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtuwytopgv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtyqpujgow.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtfenngoom.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtmovahpap.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrcxjnoio.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gtburaxeat.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtydevznyi.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtxpbxfwpi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtijlkzvoa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gttsegvxmu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtykkfgsyg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtgwvpwxcn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtlxltnprd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbefpszh.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtvkfwyjhg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtzxfdgcnb.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtqttptvnt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gteszaunju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtbjsouvoc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjrmggobg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtqmglqfti.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtvnyifjbn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtoiyspnzz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsnnyqqv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtvltgewff.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gthujxdjoa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gtzfootxdn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtyvirwgxz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtusnmmwdf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtrcgsdilq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtdwoyhekd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjanhzuh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtuikzdiuz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtiwgnyycj.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gtuxopdevw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtkuahgimp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtbgtaqqku.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtdrelnqzs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtkgyxvbqn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtzicgrukk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtoumwwjir.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtavkzaasz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtoohapirg.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gteivgxwle.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtzcbmbmjf.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtsmmtcrte.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtzwccbaas.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtcxrkdrmi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gterpsxzfj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtwjuynoaz.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtoswaurcd.html


<!-- 参考信息 -->