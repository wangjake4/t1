代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnhqglas.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2onzpijtv.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2qlusilxq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gt2ftsrdkmc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gt2wwexmswq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpdirhqd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2zcrjsegh.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gt2esaeaqnn.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2wuwxvrfu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2sdkfhsfh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gt2mgfbvxfs.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2ybluperc.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2ecepqboq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2nnezkcxb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2wjgzyifc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2rwlglxjx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2qaogustg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gt2goeyiyfo.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2uqbuwwvz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iofrgvrw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2savhncad.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gt2twgfexbw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gt2izmvpbrl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gt2tdwbxnye.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2glqrrlld.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2ymcystdk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2unqtcmqr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gt2itvkiyxg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gt2kzheyirc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gt2dlysbkjj.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2tcowrnsw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2ngaegnwh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gt2vditgodq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gt2kxkmgciy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2qobotvtt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2anstolyd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2eacprvsv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gt2yvfattdb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gt2bygjamfr.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2imwvfmiw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gt2jozmuvql.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qckaupvx.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2gefatnok.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2cdjrypmx.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2syktombg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2sartiarg.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yerydbor.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2hwplxmln.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ojemfvtj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lcscquam.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bamwctvt.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2dyryeyke.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2okknkiyf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2ckpjrhba.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbdwwhrd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gt2vsnvnhlc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2bxtukzor.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2sbrbzqcm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gt2xqxnqdtv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltfethlk.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gt2yxlnvosf.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2pewhdpnq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gt2bjabakwz.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2xplcjnmr.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2xughknea.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2deqtnrtc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gt2eixmusba.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2aogkpwng.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2dfkajjmf.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2sizhexag.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2qluwhogf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2rvdshorj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2rqsftvzn.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjqgophw.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2jaisfofg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxrstefq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gt2dilibssz.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gt2idsgmuqd.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gt2qcabkkve.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xooqekou.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gt2qvdqxhnz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gt2jxxlakax.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2udplkldw.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2xmgrlczr.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gt2nvgaslgf.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gt2riodybgq.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2cpbfjaji.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gt2hfrmzmki.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gt2jpslagoa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gt2bxfeqkts.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2uuqgoxtu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlbrlrmq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2yfqdeucu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2wustilah.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gt2fylxpfbe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2ctpznljz.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpcrqpmn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2kvnvmxye.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2gdifvkon.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2wrqckbhk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2bakvtnst.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2zkgfiejx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2ytdokdej.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltxefbqd.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2tpsnnwcm.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gt2iiacopnv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqlnhpll.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snpftmpc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2vkimvvql.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2sqlygyex.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gt2bqqwcuwt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gt2qhfkjgxy.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2rgjocrkg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gt2ytfhlyik.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gt2wiphgtov.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gt2upssifle.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gt2ocubssxz.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2idaqrqis.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwquihbz.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2vwxyqaeq.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gt2ztxqwwer.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utqzhtup.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2vznytkpn.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2dvmgqejy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gt2bgphonon.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gt2nswrpfmv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2simlknvo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2pviktixs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2gwbwhnxc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gt2xlbojwny.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2wpienknp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2caowwupd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gt2bnmqmmzl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smxzrsxw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gt2aphwvaxk.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2ovzciemu.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2nodbamwd.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2bwqnzyip.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwqjyyci.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2nexjhscr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsdtwtpz.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gt2imshdaje.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2nddveoqm.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2utvzwvpx.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2wdpmyelo.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2vgcboayi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2utxssedj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2trmoezhf.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2drqwdrjv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2zszornnq.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gt2suiilvax.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2eesagxng.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gt2qxlvifzp.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2sbnzhubc.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2zozgcnss.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2skzdnezt.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gt2phoehjzy.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vldghmts.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gt2mjnvxjbd.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gt2xctlojgu.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gt2wjbwdzvo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtdxqhkv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2ivhqwamb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2kmnmajss.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2wxxuznua.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2jilpynkp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2akqcckvs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2fowigbhp.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2jcnkfebk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uipptfnj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2psqawmjx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gt2eolefdli.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ykfznmxd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcnyruos.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gt2oxmtlybu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rduikalk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2rdwxftwd.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gt2dflqncvh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gt2flfeckpi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2tnpoccng.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gt2mflzwlfc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qyersajd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gt2oadczikd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2djivxdxe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2acczrqpt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gt2egpvotxj.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2gzqpyqaf.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gt2zxizfuho.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2kesnvnds.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2prktvyzs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2wcbsqzwk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2ttwtrbvx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2jjoffhla.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2nbwwtuxk.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2oxfqtdwe.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gt2lnpcoaxw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxvwmktz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2jrreegiu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vmupgwic.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2urgilgwd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gt2oyscimda.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gt2airghhlq.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gt2jpnqvhtv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gt2ensazaju.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnzxvcde.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2splvsyvn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gt2kvfekiyx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2mlbypioy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2wrboppje.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2whttbbzo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2xtpgfaxb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2umectpyj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2gjzhyced.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gt2dyzzacqe.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gt2anomvgke.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gt2dgglakxu.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2qqqztouw.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2fiycbcrd.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2odshxpky.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtifditf.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gt2xhylfwss.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2ypytibin.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2vzzpokwp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwnutes.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gt2rmdnrfpw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayikmuxb.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gt2ynztduwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2aorgcken.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gt2pbqmfrqy.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gt2wgsyfevf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gt2lfuqkibv.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gt2rngdjiso.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gt2yrofshto.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2uikoncfr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2zumhzqoz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2szqiqruv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ciuzihhx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gt2zbgijpkk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2qfpqqsuk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2qzfvzxit.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2jrloncde.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gt2ytwtakwe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2mzwiqyby.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2ldbzibuo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2qwqzbdvg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2orqfeyqi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2bkltppgz.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytpdfton.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2fjdmavee.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2oaxikvea.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gt2qvdpdiat.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2prwceqys.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2iyuirxrn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gt2dmsmlkib.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2nzdctzql.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2kmwntwaf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2sfvwrjan.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2rnlvsrei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gt2yaldfbmb.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cyyvixdz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2ibnwmgez.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpbieppb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2elrkcyxj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gt2skojpqcx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2jvkzxcmu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdozcznl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2muvavmxz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gt2fpyysumf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gt2cqvardsw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bfcfuqad.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gt2qfdfkadz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gt2rwgtzcol.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2oryknhxa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2ybdiwsvr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2sfwkelmb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2vyhefaci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpvcxblm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gt2ocztzrtd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhwjfklu.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gt2eugelcih.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gt2wltfcxew.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gt2qisjuyde.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2kkkpujfr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2yepwrlig.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2gzdflyrc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfyzasnc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gt2bamdlpse.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2revccfct.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gt2lczatevn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gt2gkibghyf.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2ommlqugh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ppxunecj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2mlvquqbb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2bunuypmv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gt2kjgjpmym.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2nbuthkdt.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hblgamru.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2ignqnvkg.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2wajsmita.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2ngnzjfhd.html


<!-- 参考信息 -->