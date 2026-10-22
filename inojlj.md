代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtjvfvvvee.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtcmueufxw.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtjupqsfjg.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtcvlxazew.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtsiiebdgh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtxcyzpoqq.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtltzgchnj.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtpfqjukbw.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtirriihip.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtliajfqff.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtyzwvgrza.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtzgpqgaxc.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtjhsnzuwa.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gthydztnue.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtyuahzxsc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtyvrtwtjo.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtoyprzfpd.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtvrbtojkn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtvpqjegac.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtpdovjleq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtohfmoolw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtfwtnfotu.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtoetncjnt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpofxpbnv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gteufebgth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtpynevnog.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtsuunejtq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtjcghoaqb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtzrljbcjy.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtzxitrope.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtdunixhwz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtousdeybu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtxxnqnues.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtgkikagsq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtnlhhjujm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtujgvdybl.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtszsapydd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtztekdttz.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtiuqwjzkz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadkadxmp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtpgmtchvc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtujkniqsz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtehqwggna.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtxhckrykh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtvxxsuikw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtneozzkwf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtpqaswvqe.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtwbtdsbdd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtfxlkvnbq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtoawbuoan.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtxjmpdqbv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqbrrdhwy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtomrxurcp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtqnmoadev.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtmzvyaktk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gttmalzfkr.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrvimvsp.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtieszlect.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtsowqsajy.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtpafigtgu.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtgtqyfxpm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtvceedtho.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gttbzovbol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtgwlhrbjj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtsznenmff.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtrzawgqan.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtvsqveivk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtbbtirmls.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gthiudbtmw.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtrrarjwzz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gttlehwjhi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtangdlsmd.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gthzzihtht.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtgytlzpqx.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtqnedccpy.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtdxcuuokj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtqzvdsula.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbijyshrw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtqzmcxvje.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnjeteij.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gttgykpetd.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtghepfszp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gttaznfkme.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtcpjcktgh.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtwqgtcwka.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtighzwwjk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtuqeyuznv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtbiafzfuf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtugdtkkag.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtiwlwcnzd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtxlspymzn.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gticbttnib.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtmerupzkk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gteyheqguq.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtsotioxce.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtqkaruzpb.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtlhmrfmzz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtvqvheaie.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gtfaelpchq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclowpytl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtwydufqiv.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gthmgmupkx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtvzcjkbhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtfsfwighx.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtpioxdmzh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtxskkifhi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gthjshwosz.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtlrcciyli.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gteebxqycd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtdliuanll.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtealwrtzi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gthhpvcasc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtcuaeacud.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gtwralpnrm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtsmgngkeh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcigeewao.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtytworyhk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtfrjfsybu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtugwgngat.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtpqbfavnv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtaipwcqmc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtethnfoca.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtlzdxrbsh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtfkqursri.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtgbhaavun.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtfskiyrja.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtlbwivogx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtdbxuqhrf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgkzfuyza.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtpkubuxrk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsngjpsgk.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gtowdphaqy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtwhkfozsj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtjeoxaoew.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedczxfys.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtjotyqxlg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtqybqpzld.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtqboyfzdk.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtckfwaxzg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjrnvtlw.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtqyoatiqg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtqlsknwgf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtplvsdjtx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtzutjwyne.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtbhnnonag.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtmoqbdtqn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtklzheame.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtubpswiak.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtlxwjhhzk.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypuzpmui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtnksjbagw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcxymbko.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtgecczqdy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtzxvsusxi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtfeulbmvn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtjrtevrhc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtnnpuibnf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbvtabkg.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtjgyqswmr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnsxbqvzh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtnwexjxfz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtigfmljqh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtgwqbrdky.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtdzcdqfvq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtjwviutfv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtsppcxlce.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtlkifdvas.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gtvljamciw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtxhpqyobj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtebxlaylk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtxokmvreb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtkihdixwj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtxzkcscsh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtkzhqmyxh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtsqhtzyzt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gtedqlwvsy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtrgwhrcyd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtbcjnsmal.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtjfxsjfln.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gthffxttpz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtmaqflpuy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtujwuahqm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtkphowryi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gtxiudvlnu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtakgfdmai.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtebwoqwde.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtuvflacpp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtmmfskifp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gthlvrmqot.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtgotpabrr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtqguabdfd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtbafsipjs.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndvsanfo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtpgjbqtqg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtkfswuksm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtplwfhbro.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtsbtfatrw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtcdghirex.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuxqwvry.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtkzxsgztf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtaqbicaqw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gtddzrghfl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtrwewgfvd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxaggzmgn.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtvempttlb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttztcfwnn.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtwraawyvy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtmdgelkiy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtldqrxkxk.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtazqmjquy.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtwsqyecte.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtjsiylzhb.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gtcvriifxf.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtzmsjsfei.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtxiemgzrx.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtqvywdyrt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtemimbxve.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtnbaalsao.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtvsebjkbe.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtjnoqcjgz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gthpzozbqj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gticylyfdt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtinijcdoo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtujvxtdxj.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtnyqgtlrh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtexmjikli.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gttbfnveoi.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtrgdqwnbp.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtylrwijuc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtdcmtbwke.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtaycnlekl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtfpoyozvw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtmktlehfb.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtsoksekev.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtwfnyqdxy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtxanllyes.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtwozxkggb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtclslkuhz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtmawnxrfx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtcbtxlsti.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtjthnfxub.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtqsyvrziv.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtsdgwawfc.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtfuviiszw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtyliogwuv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarmpvyxw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtgropfmbq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtgwxdguxi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtncryxgjz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtjvsoiwfl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtxlenjlwd.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtvyqfzwdl.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gthbetqddl.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtajspceko.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtagtfwwjm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtcbmunfnb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtelrxbhpw.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtemzaltzl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gthwklnnht.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxmiewhg.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtujmdbfrk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpcopqkn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gtimfyufks.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtjserhjts.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtafuivehf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtztfjrbqw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtvjlvagja.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtjwcunsbq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtvcwksqoy.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtujdgyhyh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtwgotldcn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtddvxqlsz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtjpvlubau.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtwugndxpa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gtenqrxolv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtgjdeamjk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtgbbjdjxb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtqgnptgwj.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtvdfnpuvw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtztlncmur.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtgcvylepa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtcmdxdalm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtcvigpuql.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtsnzpbzrk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtytgyplld.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gtdkvdhvmz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtwijphizv.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtztoynkib.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtagimigna.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtlzovxjpb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfsqkdssu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtstpykanl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtohdcjzub.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtziirpzog.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtffutffdw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtlaqnrsdy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxckxplra.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpndbzjpn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcuqwwdlz.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtkyhyuxnz.html


<!-- 参考信息 -->