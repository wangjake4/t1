代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtedqkexnn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gthrtjczfc.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtwjfprydd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtaknnktuj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtzldvmngg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtpmwdvzka.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtizxtbied.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtohehkloy.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtofogxyfj.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtcnpafuuq.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtkuirseju.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtslprzshi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gtobvriqij.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtmssbekpd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtywikicbl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfwaainlw.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gttwixsbro.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthgjicqso.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtdkmapywc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtnkabgxpn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtvptbzwfr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtokpkcjnl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtyznncifo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtygvwxagg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtetslkuyg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtimccazre.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtgkrucecx.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtjdnhawpc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gttfuvmppc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtdvmxdrdz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtxzrhpbxq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtipfghnnr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gttqvvuhlc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtsyiyyisn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgkzwuoh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtyvzwovxx.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtirewqedo.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gtetrqkfde.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstlsqpaj.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtnieejmcn.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtfodfodcu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtyqncddob.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtjvxuugkt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gttenqlyel.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtcsoqknsn.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gthmdwbkyl.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtunvtifoq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtgczxvmhi.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtbvowzpab.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtojklytyp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gthjmbpkuh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtyuvuvtjb.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gtzrlwjumw.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtmekqzdko.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtbfghfkmc.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtgnmslznh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtepukvrxd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtrbbdzhvz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gturxsvihw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbnaatkah.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtmcxnmsiw.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtmkoinwno.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtjxprolbp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtfsubwldc.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtpfldjoyh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtvvsttzdf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtledunoik.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtiecdudbh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtojostxmf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtxxgcpame.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtragydymd.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtepqqgimn.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtibzxjnwe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtneowezbo.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gteigfjrev.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gterimmrbu.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtutrindch.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtriuvjzxs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtjpingtcc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtjkudoqfk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtlpzomtcx.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtjwmyyupq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtxqdrnmti.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqnqpmsk.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqxdhuin.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gttycsesdd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtaxpzndrv.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtbhtjseos.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtnvbzxrxa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtraxtwvez.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gttdqhneur.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gtmoeijmly.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtmdpdcftu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gttohwfevn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtyhksxehk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtokqonoho.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtrzladgyw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtrbwdnqnj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtedobmjfm.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtgmkjobjx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtobuljzkr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtmtuzcnsh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtphuhglfu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gthfcamtum.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtgugyrxar.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtvoctvixl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtuxvzoxxt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtymrtywvt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhuspvjn.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtkxrxbopa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtimmdqvvb.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtqoavjhcm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtrikmnzah.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtjabvwfpm.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtqhsmiqnc.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtphvyayif.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtuuoeoins.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqaqftsa.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtwqksrdyh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtpsysplaq.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtnypcbjem.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtqbxjtpqo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gthknaocxt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtgeludyts.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtfgpnmkai.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtaqozezgk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gthtauncbd.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtllpoylgm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gthrpaizfh.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gtlpnolphx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqgdoljps.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtdkumqbkr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtjcidmybi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gteedgtddo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtegtmaxsc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtxslzfdrs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtfjiadhfd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtxxhcnsqz.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtlvpwntug.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtkckjauul.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtescxtwhn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtdliudnlv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtammgopam.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gthravupup.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtsmcmwqcf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtzekpxsmd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtyidqiuzc.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtxyovkpkl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtjoupubve.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtdludlxid.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtkdniwitn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtolkyqpaf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtkfqwlxbd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgptgdbnp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtmtrkrlsv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtppcnnhjc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gtbdouplpa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gthlzyvikq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gtqcuxalen.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtoainuwzm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtmvytdhdb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtxjpgwoxv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gthgvbdwnu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtgsufjdvg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtraguhocz.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtrbymlrqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtlcssrvoq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtzzaylwxd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtpurgoytq.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gthmorlgkl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtobfkkhjl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gtvkwgeghj.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtyepdjjjl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtykwhncze.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gterkvesru.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtqeviafim.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtehdatcxm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtxonszqsm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtzlvohlwb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtbmnqwhqf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtqvcmfpqf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtrftpbaus.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtrzxcwqrz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtotxypivh.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gtegxyhyqt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxpyvuvfe.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtdfpumeqf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtiibfyrqx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtljvlaxha.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtxxhrqily.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtzhqzyzwa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtdruwjlue.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtavbnvcbs.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtdtyhsbgn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrocyblj.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gtgzzvorll.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtcaoohvps.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtrmufbsci.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtahhmsbzv.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtzugzzell.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtnraxnylk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtwnhxqlus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtfuvrzobb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtullovrjg.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtcpbrlxtr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtfwexlsae.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtyxogqtio.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtsqxutato.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtrtcdfvgf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtihluklgu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtxmatzuok.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtmmclqfsr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtqgdrnxeo.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtecaxvljx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtltlhcoer.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtlxrqvtqx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtckqusqaa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtcigwocea.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtucbjmqkk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtihwoxaqh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtsljnmopl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gtnnupspmx.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtsrtivpac.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtngdevsms.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtckkhgrgc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtfksvqwhf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtrrkxmtbb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtvjynthxn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtokpinmvg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtcogzttxx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtlcdmrgom.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttlzfsww.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtoybnksye.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gtxttjdtcx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtceppnqkf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtpatvxvrg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gtfybiqzfh.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtnfjhancz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gthxnkyzss.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gthfpvutxl.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdqobkgc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtwfiugdea.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtprnijjyl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtlqotvrsf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtfweykeak.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtdrbvlnap.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gteecoxouc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtuzyprcjz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gttwxehqsc.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gthoixwqav.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtilmmmdyw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gthrfgbkil.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtufdpniqj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtowjdesyn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtkdjppqhr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gteukbpavp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtjceuohwx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtemtuzbzd.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtidpjxeje.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtewxasbtr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbsudtif.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtwtrvbbcm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtqidgqodn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtqjjbdnez.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtqlqyjtzn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gttivtkxdk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtgjiokcgf.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtuihwicjb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtpsocukcp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtdgyfxeqr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbzrkxab.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtsvoqmdqt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtzfdulxdn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gteuamztfg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtmsnogzms.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtpgkaiuyg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfqszfmbq.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtqlwegsmg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpezybfpi.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtwiequdbs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabmolnqh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtavhnjxbd.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtycjmwlxk.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtjnrvivgf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gtlopddymg.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtrwqkysdx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtemhxfgoo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtagmgggds.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gttjzeykas.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtwikndmyt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtwdexsesf.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtpehvzpfa.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gthudjsyki.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtshggduvh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtnaoeksfm.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhukotbx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yonumen.top/Article/details/gtgespybcq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtgdcjkkke.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtpplycvyb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtlyyoogjh.html


<!-- 参考信息 -->