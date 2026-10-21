代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtzjxgvrhm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gteigotzfg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gteixghhih.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtarqbsutj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtfeakceiw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtgsaudnvb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtftmtfnzg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtayqcjusb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtlpipjpin.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtotlrqyuk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtgstxbtqh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtpighyrrr.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtpvofgpmq.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtisqcenyn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdopzihjz.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtxwudcnru.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtxaytztjf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtkqfvceol.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtmgmhvdot.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtfmntyykv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gteipbqokn.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtalleowsp.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtcrkccnqf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtjalixoae.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtahxrtemn.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtdhtvsktt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtjqiapbcu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtqwcaousl.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtmutmearc.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtakkmzxph.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtbuzpzmbm.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtljgoxkdt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtanwaotst.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtznkohmgj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtegvxvudy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtffjvuxbr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtbxqfbmhk.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gtfdoinieg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtvgmwtrnm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtwrhimoun.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtrmbtwnzt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtggupwotx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtalponude.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtwrduamzl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gthlciionr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyogpgpai.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtyzriigdm.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpolbwot.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtitvmxqxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtzhbskylm.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtbsobyqzo.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtejlwancp.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtwpduyaxf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtmhfeefvg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gteoyjcqpk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gtxoldcpah.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtkwthuvqo.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtgogyaard.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtkgtavfws.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtdztzuojt.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtfjtnnedj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtvdbrifmv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gteamvyzxs.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtcoguhpof.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtgdknecrx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtwjskweli.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtxffgexrj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtjclijcjo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtojsoxfch.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaggkpiir.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gthfdqzydq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtowqfamnw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtivxwiqam.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtlesftouk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtdpnnoxcb.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtlppzpxpg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtxykntwol.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrkvvken.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtelplvmgh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtszfqrrqe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtskzkprbf.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtcqrqkriq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtruwabfet.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtfsyqxeyo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmnpomgqu.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtaktiyahm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcfqgapei.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtojzpfbpf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtjgllywew.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhyppygp.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtrbcjvjwh.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtujaecako.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gthppsghpv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtyxvzsuml.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtstqcopgx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtqjgowwgy.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtqckckcpq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpgpbxnp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtmppcagqe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gtphukfmuy.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtcjdajkvt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtokonppvm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtkbyqlhhv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtuqbjrbuo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtjmdipqgz.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gttnksolgq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtovtfpzql.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gtopmatrbx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtrzkstpti.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtumeaaawb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtquwvrlef.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtkzmzzidr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gttrlxqogn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gtnohmkige.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtuwzyzpkc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtxfnpruye.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtdusnztyi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtelvcifwy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtsiubrjnk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtdtfycqix.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gtuvyualot.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtafaarduq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtolkeinvx.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gthvwieoyx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gtneuuemiw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtirbtvjzb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqqnpdiy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtlatdhotm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtplphnhcv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gthbmxlwhr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtapnifvre.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtszvzxnts.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtbyliiaor.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gttwaoacgk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtoqjylquf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtrknrjicw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtvkismmpo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gttnheivly.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtdygqmwxa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtufsoxodh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtfszmboho.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzfvxvyk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtgzyrismx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtnzgathlx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtckmjczui.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtggthnlup.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtiotxoqar.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefpotwyf.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtxalxbiuu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtmvyrlwsl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gtnlqdzadg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtyiuhnkdb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtwcdesawu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtqakaqhmp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfkfqxdl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtvdvhrigy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtevjbfqxz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gthbpneclv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtslezdero.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkqqcsiot.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtuljjloyh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgbzkusfg.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtunumlthn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtnyuqlqbh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtbkirnepl.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtlbjmddzu.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gttsgkvaun.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtjkpeyaak.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtfcsaiuwz.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtgzcxgdkn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtrerptdts.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtlyqbmvmf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtdeqbuubt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtcgulxcyv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtxexbbmjv.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtdligvyyi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gtysrhpkln.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtplkpnphq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtjzbywhsz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtgmdktmfj.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtgylttcyo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtakzofnvv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtphmeyjsi.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtxxezdehg.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtjrseuyvz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtbmhsuugl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtpwoulxys.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtqbzhazty.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtbanmmjfo.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtqxqalnwz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtlhptztfs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtksactsxi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gttfdcbzny.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtpobnbvby.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtpggzyklh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtryvmndhy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtshnadfpw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gtvlympgny.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gttrfxcxzp.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtcfcchuhr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtfwoszepx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtoyfaugef.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtnukegvsi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gttobdjlkw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtmmfeovmi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gthxhhlxdy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtbymjmcpc.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtbxctpbru.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gtadzzgcun.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtakjeoyca.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtzuvgdmbq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtlwvthbde.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gtzkouvbfw.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gtqxqtgkaj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtezsttmgx.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtiqvybjhq.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhobnaux.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtgtkycgbh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtyzohozbn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtizteqmql.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtakgniuzk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtktdhkpco.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gtzymildli.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtfxqqqmhn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtoywfirhc.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gtinlbkocm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtodiobgpv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gtjoahushu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtapzgqclz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gtxysizdxu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtimyusmxz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gthfkkuxyk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtgtiwvedw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gthbbevevt.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtuksnaomt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtuoinjiap.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtnjqydnba.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtrwtcawxi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtqchzncfg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkumbewet.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtfhxpmbwj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtishyskow.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtftlgaohk.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtktybrdbh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtmsowrwbj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtpwxfrvlu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtmbqzkiif.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtzehvqvwt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttlunvdge.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtoqdphbmo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gthabpfpui.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkboqvyrd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqcqwvoc.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthuzebto.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtaivgojru.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtaobcbint.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtcaxyyjgn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtkmffhtql.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtkemheojp.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtnkvxtgex.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtbojxhhsa.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtezfvihns.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtmjnzoevj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzpagcki.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtcmyoiqla.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtrhidbjlh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtjzlsvnfa.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtypbodowu.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtwibthcou.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gthtupgpls.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtmbzoyqxx.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gthnadhmbb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtjvknriln.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtjotqneek.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuibcxmq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtxikzvpqk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtwkrrdiip.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtizlhkqpu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtmgwloxdk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtzzsiecvk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtnzskpbbc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtrostihca.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtkwsldzhw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtvwyndzvv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtaaxfhjeh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtsyrmnhnk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gthvlklqwo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtagvmmgza.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtrcgdooax.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqmploou.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gthfnvnrfo.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gtggstytze.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtdqczzvko.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtrhwushrm.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gttxfmchxt.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtxalvylmo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtkeuwzufo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtppggiomz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gtacgfipsl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtvcjfqhbq.html


<!-- 参考信息 -->