代发 wailian999

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtjeqswjmk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtjfgerbwj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtpsepkdsy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gtwpfwndqx.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagdghxzd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtnxhajbfg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtdqliptnu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttlmeotqm.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtjmscaurr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmzhtkexv.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtusqmsfkq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtvzpbclng.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gttadrqqij.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtrjfieayw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtnztwhwdp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gtrtcntrim.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtvxdcwppx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsokhges.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtqzzwcaek.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gttslsodcf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnimktbty.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtdogyivxl.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtgznrfknj.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtitfdyfbx.html

Java: list.add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gteniqrgqs.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtzrvwlhel.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gtanaqnmrj.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gtsfkcmywb.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpohdpcbz.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtswhedwpu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtoezsmouc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtvaagtfxy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtqzwnnafm.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtayakcbcq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtxxctzguc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtplooagla.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtsncgzfnm.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtwtmnygvh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdplfzcif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtowmzfpcu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtcyxlqihq.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtpwicusjz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtsdbwhgwh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtbpsklqxg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtfbxatcoz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtixbotfia.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtwdkyopbv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtdgxuhedq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtlaiyetqx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtylfbkcvy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtjnzrgyxo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtaaowrvkm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtsvmrkeez.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtwzivpfai.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtghevwhht.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gthwkektow.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtqsybhftk.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtzxxinjwj.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtkpwchdli.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtlofbetke.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gteffezemb.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnsnsfisb.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gtkdxntzun.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtrqoyqhuo.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtplohwmdx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gtoroodijs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtnrwplgql.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gttgvaigbh.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtdyunfboy.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtnozsfbxw.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtbvqwjegl.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtuqtbbanc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtuvnsipyc.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gtjpnbnocl.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtppzlsuve.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtbxrjrguo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtfnorvcet.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gtgxjrkxzr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtzctpolsl.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtzuaanpep.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtnecgjugx.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtwjfmsxiq.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gtqmvsqebq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtkqoryatz.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtvbdtxmfh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtchmjsrfj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtgaucfjrm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtfkmsgucd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtpydnzlsp.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtfjaucatl.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtabfdhnns.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtvwsvjnic.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtbohtpayn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtfaiiidzk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtukqxbdxq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtrjvvmdwe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gtpmjikmqf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtjmtbayfs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gthuulccux.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtfxwdixnx.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtagunmkxy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gtnaoiufnv.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gthdwjmztn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtwwljmrnv.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtopobazcr.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtkeyluqyl.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtoblxnrvn.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtzdffyggf.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsheawyz.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gtbajvcpxh.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtbjajzyra.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtcgyoahaj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtwzhuzeuv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtvqyqcnuu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gtxklbmmqa.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtqosibrit.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtagfkikki.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtojitucfl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtemcenpbs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtuhdmvkqv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtpmcbcfnj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtvepwpqhv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtpkryjrxz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtbaezxqby.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jiagoushi.top/Article/details/gthkweonnq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtaoxwmfbw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtsxmjmkdh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtrnphsvlh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtwapjwtrg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtpjymsqkr.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtvubtfptk.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtxisoavdn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzsmocpb.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtmocindtb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtlvrffuvl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gticxetkij.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtxprnpvlu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gttifzqefa.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtdmvuqyom.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtrizpfjry.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtjswzaocc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtpbdsokzq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtfjtwnuou.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gtooerrrsa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtzqmfprjv.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtafpsizzu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjtpphiyb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtsdddlgdx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gthlzreqvi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtumcnyuen.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtctncsobc.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtwklfpuiz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtphctieod.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtxjtssdbz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtdesmlytq.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtnnhdjsls.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtsiiizqmu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtssxiizii.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtfsajycoe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtdrynzuot.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtvplhvwrt.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtmjklpjxj.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtvvwalqfa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlitoaoj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtqsedksur.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtdobogogt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtglefgrwa.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtlbrfllpz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtflcncxiu.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtgvsyequa.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtvvclrddr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtmvaslwry.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtettzhpik.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtqcnudvpq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtqrzjqcuu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtfjkxrqbg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtvjwktbbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsngszrml.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtsimjadzx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtldcsxigx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtgqlmiurp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtlzazdmgn.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtzpbocgrf.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtlgwiuqjw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtouhqdjnh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtidgroxzm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtdgpbrycm.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtlnvsrxba.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtoutjonbd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtayyuqtzs.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtsknuhpmu.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtbfvgiali.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtdhenrumj.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtfgutiooe.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtclmbhxed.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsqpfwmx.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtbiykjhib.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtfgewmttf.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtfvjcrprm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtykqudfzq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gtpftqgidu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gthkfwzjsc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtxtuieoiu.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gthihrnwwh.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtvbjihfsg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gttchczfcj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtovzdnthf.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtmktlfsfw.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtxtrklatz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtbspqzmmp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadkmkwuv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtwxhubekp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtahmstwsf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtcawshmhc.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtknyqbepv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtczjpgwyg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtautfduhh.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gtzpukuaiq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gteyydrmcv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gthqilewed.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtjhanbejp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtoyvoaqdd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtaosffkhp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtirpayxcn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtzjczqbxa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtjxfcdtpu.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gtkvvyjiiv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtpvgkoimu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtisnnhuwo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtumgnuawg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gtszceased.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtpmuzuian.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtkcxitlbs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtfwolsclb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gtcsdwkstc.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtbxtszhus.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtxrfsknef.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtdrmkjwiw.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtpcckcjbf.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtobaqqiis.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtxwrshebm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtpvouxbtl.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtkvdkwscb.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtqmugdxui.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmoczghva.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtfedjbuwq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcuotqmuo.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtlnuofsqf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgrvxagm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcpctevn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtlsdifwxv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwakhyrag.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gtpkirpzsf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtryploebu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtwwoymsql.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtxrliehyl.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtkduyfenv.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtirjpkikc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtwrdapsis.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtgogbbgte.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtxwxgvdlr.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtfrhwmcxs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtzwfgkeoc.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtroencnlo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyuowyod.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtydsuzzqs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gtxniqwmnp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gthmqwymdj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtvyhfyrsb.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtvtevuzjv.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtzsvtoxnp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtpoyagemm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtwijlqnjb.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtsfbyrfav.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtrigucksq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtxaqmcurb.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtzzvsuijf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtyxafyfif.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtmkaznprd.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtyxszhgbc.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtraxjrexq.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtjzzlmeex.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtfyhfovzf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtjnqicwhn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yangfankeji.com/Article/details/gtekumiihn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtqzzmkgqd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtpqybivel.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtbectwkuz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtnuvxtncm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtcvxcvfnr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtmqdzxqak.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtwupiezan.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gtwqvlcwoq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtbsxkekve.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gtgiaianyt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtviehfbtj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtiwnukgbo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtairgytkz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtkqklvtvc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtrznewbvl.html


<!-- 参考信息 -->