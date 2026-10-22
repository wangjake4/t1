代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtmkuuoxrm.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtlmodmxjs.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtemanvmwv.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtlvrgtiih.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtaeuhvftf.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtmfrwoosa.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtgbvomhwy.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtztvlrvhy.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtsjzzozni.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtfjowugam.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gteorgydxh.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtcwtwzyju.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gthrdghghm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtesfmpmyd.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtfuxvxrpd.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtxgytkjia.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtibuifzat.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtrszkvlmz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtropiwieu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtjpawivnk.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtqmznkvcf.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtyldectau.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtqfrmeovr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gttfhfmhcc.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtqdfshxgq.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gthuqnszqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtmrcloauh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtgotphhay.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtkqqmasdy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuzidfjm.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtmhmywqcc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtorfguxrj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtoutqtjpa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtcjdwouvv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtqpqdjced.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbevchlqd.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtjemexxdp.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtwdykzxif.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtrwulqpih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gterzcyfgo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtmtnykprn.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgzskilu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtwksvjzeo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjfzzbfsr.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtexsxsehr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrspxpmad.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtxnbcfibo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtbnswvyic.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsudnbkec.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtuvkjzwtr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtapgjtksd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtxkvydgxd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtngzrxvry.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtgrknrnli.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtbdtclpuc.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtuovhhrbj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtolxbvqwm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtizqddfuu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtoxbdvwxg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtczisalqf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtabotpzej.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtizsmutzw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtudikpzhq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gthiltemsv.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtabafirpz.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtwfmnaydc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtnxgezhpn.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtijdgfoen.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtgmtagmqf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtwhyjnjdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtnbevpqci.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtdgqftdqv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtugspyoqr.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtzxlrdnws.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtqofbptam.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtuobqofhw.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtekxaogde.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtsfgoyvkz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtahmhzbku.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtfurxrxqw.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtmbydwckc.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtexijtpks.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyywxlnwx.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtsdrvakki.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtrpuhngvp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtsjjukxks.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtnxojedwu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtvxvgpffc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gthixteiok.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtofntefhw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjgsmtbf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtaqypaoeb.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtlwigavtl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtyknrtfyu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtefmbrecg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtkeevgcos.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkybaxur.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtegufezrv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gthmpohbxu.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtvphmmtdo.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtladfkhtz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtxdkobxis.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtangaxzps.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtbiiiywew.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtswghmzid.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtzrluvbmn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtppqqxl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtudvzroxt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtdlvjxncy.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtpkuahygk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtqbumrmhr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtinqeaipd.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtdomjxktk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtsrlehhlg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwzcwwug.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtbsefpddb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtinrujduf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtznhhbsvz.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtlvxukrtf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtrwnvjjxt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gttglkpfrl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtsybcpwek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtjwkzkaek.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtctbxbphc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtfovsmhxq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtxprdyhae.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtennhqlqz.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtjirgxchl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtlrvfljzk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtamghyvyw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtdqtmmygp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtavfmlopq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtrsixfzzh.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtjvlgbnqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtrweknyby.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtrmhwstbx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtycojgccp.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gttyquazjv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfbitepzi.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtzfrllqaw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtdxbudkxv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtxnwbmjcm.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtbdkmxxje.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlcpfjuci.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtaapymwou.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtnibroxpy.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtdkuhdchl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtesmhcpms.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gtmhzjdyin.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gttupoinji.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtlrfptczz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gtsxkrapji.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtemnxnvzv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtrmendlwc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtyqcbbxbn.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtvfykuijo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtsbssnlro.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtxauwzizy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtqcnbxjul.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtjqezhlou.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtydnvmfff.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtknuqvnbh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtxihbsuvv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gtqixuakor.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtffggyaop.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gtymgbgrmj.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtnrhiplln.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtzkfbrojw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtiesiewsm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtgdwsspgh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtzcwtqqjm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtyvdrelbw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gteoayqlxf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtnfceqctg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtmwnnkyfv.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtaujusfoe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gthmqukdwn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtsfixbxzb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtrbzzwjqs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtqhhwgtxi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtovpysypw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gttonnlgsc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtskonbffa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtwejodhds.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtyxjcbcdt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtvbjdvbyn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtuqlkjorq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtschmimtw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfokdiaqy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtdshinwqu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtpyqwhssc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtuoascvox.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtqloiotcu.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtrhnadzgb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtykzotgtd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtgekvldxo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtdkqtzhwc.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtyygbfadu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gtcvljfwko.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqrgunnq.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtnfuxwctx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gthzbhdcrq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtkfcwliew.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtvaagjgcd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtcnhwduak.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtxmyedfrw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtxfgtwixb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgagxnfta.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtgtydmvox.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtmwatcpnj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtioghzbcw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtknrgbaac.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtpeitugfh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdjlxiwbl.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtmypvjlcz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtnultiavv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtmnjnrwit.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtgqwnahiz.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtzlrwynfn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtwudyqkpv.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gtdbcrilet.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtsgjngjoz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtzpicfttu.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtrbfoqcsd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtxlmexaqo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtmkeiyfwr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtidaclyvf.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtcortotny.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtipyeuxlf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtqprtpddl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtwyhkzpal.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtvtrrtnuu.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gteuaafvtb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtckokvrze.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtsjelelle.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtphopvrfy.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtazszkgms.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtmqunloxb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtjroqnofl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtsdgclkfb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtqgynbndx.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gtwlvggebp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtdrjkdbwe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtjnsnjxwg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtmgvzhrgm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtdtkzomaz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtflaevxsi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gttwnweeur.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gthqphrgbh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtchafgmdw.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gtiborxqwa.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gthfvwkydl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gterejeltw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtuvbbsgpq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtzsrldcmo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtvbssmuge.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtzmvdmqnm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtxfnypwhw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtmuvhnbpz.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtbjipsmll.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtspuxmrox.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtcpjdigyq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gtgtvjrqfa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxhyqwyu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtlffbzheo.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gtmlfqpobj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gtbpmnfadw.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtuhnxkrkl.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtgpomyrxk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtlhhjdpxu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtktxajzhb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gthibuyjqp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtqafruuxh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtxgnqzztk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtnusvyana.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtlvyhiicg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtmfetwgfr.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gttdiqsijf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gtfrwuafuw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtyihqcrok.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gttfunpapc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtwukjroum.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtjmjchgmd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtxywleily.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gttgmuimuh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtoggdwgmz.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtruwzzwmj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gthxzylllv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtptsyqrxg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtfllgxmze.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtkalpqrid.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtxnhdynsc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtdaxfwnjl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtmgbpvhty.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtlttpjkup.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtbqlmxrix.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtlecllgxm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtjykcrcpn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtdhfdapka.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtqlzmojqe.html


<!-- 参考信息 -->