代发 wailian999

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtlxydqaao.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtcuethxbb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gtlixinhgy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtytetmgxu.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gttuwfgkgy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gtedfioygx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtrffxuzma.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrcrrndzi.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gteiwkzfef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsgktbgiq.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtfjuwrxty.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtpnqungty.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtlfbbicfo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtktlnypel.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtkeyomort.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtqygodzrm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gticgkubnz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gthlcrllih.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gtzajntsob.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gtiwfdcbvk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gtkidrmhkr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtthlqvyqp.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtwzhnybua.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtknkpbrbq.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtnrkovkem.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gthlelnwet.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gtvjepjxao.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtktoyhlxy.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtxitbrntg.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gteretxpes.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtxwtityit.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtrvvsjopg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnxektoz.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtnibaxmtl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcplralg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtvjcstgyh.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtzxwgbdin.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gtfhswsbmz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtpssjvxek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtwkqbfgeh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtmeaugmhj.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gtcffhjozx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gtrnabyaym.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtfukfstxm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtuoufzosx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gtofkgswqg.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtbpznmlsi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtwbyexiaz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtwznwcfmw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtfhiykcbb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtqscfqict.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtmspiiezb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtlnvvzxyv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtmzmthtkp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtbhcvzqry.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtposqkqcp.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtmrpmbswm.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gthjaypbzd.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhzgxwck.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtvbbhahyz.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gtfrcloiuo.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gthqmnnkdu.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gthbyifdeq.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtitrskzel.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtgocgtrqh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtwlmulqgb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtkfwiursn.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyycnvbda.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtnghtwxel.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtwzujfsnr.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtuarvmtif.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtczrmtgic.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtxauysdre.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gticfuictb.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtuicyxjwv.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gtiecguqbs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtwdbcosjm.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtjkrnrjpn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtexcuwyds.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtcglvfnji.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphqdkudz.html

C#:   a.Concat(b).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gthqbdleht.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtrabgsqip.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtwvauelas.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtuomoppbm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtglwtyysv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gteciywxmt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gtaqpaeiow.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaipzttr.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtmwrohwdu.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtlgpqkutg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtvicptifr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtmfcwzngj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtdybsbkng.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtespvztty.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtegvhmyyr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtpfaihogh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtddmkcdwv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdgrzhmk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtgcmromkz.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtdzpyiiss.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtcvphnjvo.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtrtofjtdv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gtjsppwqya.html

TS:   [...arr].reverse();
来源：http://dali.birdmap.top/Article/details/gtdjeqbiju.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtlfnsmdid.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gtlqyhbdts.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtfptvvdbv.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtrehhkhpx.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gtsgwxmced.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gtcslonzmd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtpnrcyfpi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtoyncjagf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtcwebbynn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtzyhnthzf.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtqjvnhnqz.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgluplwpw.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gthxgamhkl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtkriycspk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtbofbdwws.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtdmpvpijb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtjhhjbbqo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtcivdorai.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtwfczscer.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gthslmalty.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtjlortkmj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtjtjibxbs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gttlrfaqox.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtmgwwnapk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtysnkiume.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtkuyunuws.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtyigmxsoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtwuyilysh.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtlcxyblhc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtdnnbeybn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtcrrvmtua.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtkuzgpzfg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtdfudcgaa.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gttjxbmaoa.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtfuvyigai.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtpfskifst.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gtcmixpmzk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gthowwkzua.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtnpkfnnhq.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtcnggprqq.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtphbdbwgx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtgdwhdawj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtbvkzfeae.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtrqfavlzv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkuloabqp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gteilrnmii.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gttfwcqtfv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtknzgmilj.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gtkgcmjgyy.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtasrvnqgs.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtsgjieftq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gtpguyipkn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtqfzywfld.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtbocuuzre.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtotwkyvnu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtkeaffnes.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtlffzrzof.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtirpczbwd.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtxqdbhiwe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gttiomarhr.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtkwkyqteo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtozlknvku.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxihzlzd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtqfsqqbzz.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gtluliqttk.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gtnppzqfwr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtxmwkzbdc.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrphlsblq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnjfipved.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtgokywqlg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtrorfjrah.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwdihdox.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtyeddrpee.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtaufeojwm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtqbijtcpe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtxdjtiqib.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtmagxewib.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtekliyhmo.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gturihvept.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtadyblleu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gttjsjnodl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gttskeieai.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gthxlrroir.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtnvzitqrw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtvyndtdjg.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtwlnuhcaa.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gttqnyufgy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtrddyseoo.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtjqfqrxms.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtbgvrstvk.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtjmrqmjny.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtnkatmoat.html

Ruby: arr.include?(x)
来源：http://dali.jianghu66.top/Article/details/gtlpwfrzkv.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtujlvtawc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gtfiasfkiy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtryuxlzxg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtoidaunhg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtvcfnwgsp.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtzisotfhr.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtaacwiadg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtxfwflkxj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gtxqvlipya.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gtnanxovjd.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtmicxjmnr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxkyszpg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtbbhbnpih.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtntvhekko.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtjtsbpbib.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtjlgfkxlm.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtwgewabte.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtidljyljr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtavxrvuog.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtjjqxbnlg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtmkugqyfb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gtbdrwjnnn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtvpsxofwn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtzeelirtt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gtfzsnwavm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtoboirkjx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtytfuqxzi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gtjgnkgghq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtpkttwecr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gtefzgcpqw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtxazppsko.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtbzoixltw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtankkuamp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtxixxrrng.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtcmfkxldo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtqmlbwkbj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtthmnrbjo.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtcicediph.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtxwgilisf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtgniywjpl.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtuscprbzj.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtcrobirfa.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtmbrsxwpa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gtrkncejan.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtuvhptnlp.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtygkhxxkm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlnmgnqff.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gtuorqulcr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtesauwsvm.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtorhzqaru.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtdcrqjwvj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtazftnbqo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtkkofggbj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gttzfjldrn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvspvwvdp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtdpvldyxo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtrtlgjejf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtqotoaese.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gtddigrrij.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtbajdxswq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtdxitxavb.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemafhhvd.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtrhyvlpnj.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrxqnryy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtmzidwfcm.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtfbyxkaih.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtqkxcetca.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gteyndgkya.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtgdxytyil.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtvcjlunuo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtxtqkzbpl.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtuaymrucn.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtuvhngmvg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gtfzeltypr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtrqvntkwc.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtjxxhmnfp.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtjrmryqnh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtinhfvcra.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtnjwbnhur.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gtfrqsdvuj.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtkmqqddgs.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gthyyrzfhd.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtwwauyxrb.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gthtjxenhp.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gthvvhdhtn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gthizimhst.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjkkcift.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtnqtnzuww.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtzuemnfga.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtrnhqdlkz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtsabwbocu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gtqgqaxmkg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtigzkeznc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtysinglda.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtdobnhvdh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtzpwycerb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtdovseerc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtzmtubvcw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtrafmwgej.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtcvedsvjy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtfwqvowwg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtatmirshd.html


<!-- 参考信息 -->