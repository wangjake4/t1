代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtnprtwdzs.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtnjozevqh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtximbpogs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtiyegqlyj.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtthrqtjjo.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtmtwtscir.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtesmjwgei.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtnqojyukp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtgruiajkg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtxxiddegp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtnqmghhjy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvocqpbz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtamyfujye.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtztbayefw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gthnapjfke.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtifrvjoes.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtivljtzmu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtvlbkwvtq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtnvmpynij.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtyvcptpxn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtpeiqzopo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtycgnvrme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtfpljgjnv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gteayrwtso.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtdebwfjuv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlexeuslo.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtkxrzsuix.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtgqkmjkqv.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtdzyxdlyb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtfshnaoud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtfrkpaqra.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtfxcotheu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtmonkszij.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtluakcpcz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtxmmaibvi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksolzjcm.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtjiayqcds.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjnmxjzb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgievcqfc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtlbcyxmhz.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtvrrsplwx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gtffuqqpqz.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtkhlatfvo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtwibuzfoh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtbshzthyh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtamakpzbh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtypanlocw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtatovbglm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtjgzwplez.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtjspoqyik.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtadorkucg.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gtuoeeckxa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtdqnztfhn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtjkzpkzed.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtbjymuzvm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtoupmcthd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtmypfugoi.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyizwxlo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtjihkpnyw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtgiwrwlbx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthfoajiat.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtyxuohigt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthityvinm.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtkhvfwrtd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtoimcnssf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtqqmogumk.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbtbsxpar.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gttfryovwu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtxevrzsyn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrbekmxjj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtshohbfeu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtpxkurtpr.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtuewciwgh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtliqwysdz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtptscvscd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtgsxungil.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gttuzxifcj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtmdshvdqh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtgumtswak.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtlvlgtmsq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtqqzllzjx.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtyjcgsbzm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtsupxqbkz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtoyjymkmf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtkhrdceck.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gttyevbbwp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtiydcablm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gttzzunrtg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtunxxggji.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtbcsmxfsx.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtkbontvqb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtkmvwficq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtvlybadbd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtnxvsjfuk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtfkwhbvok.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtmwzmtszy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gthojnvvuz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtcxfhmska.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtfzgsader.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtqarkjfot.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtehljklgv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtahcdcdeq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtmeyvbhpd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtlyfvmirh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdubcvqhx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtnlysglwj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtszipimvr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtkocvybag.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtizegrrjw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtrfmryjie.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtnvlmrotp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtswkwyuou.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtzfybjipz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gthtmvvgzw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtkjzmtbsj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvudwhsea.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtbhhsdare.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtrldsxaxj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtogpzepaj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtovovdhdr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtxeolxbsz.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtbbpctfnq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gttoraclab.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtjtnzxjsz.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtdirzmrse.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtkauszwyq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhqrvaon.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtrmrhjkhk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtmkofhldp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtfqqhkpwl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtjlptvuir.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtnbfdlvms.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtttvonghg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtsezgdmhp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gthehbamjt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvwxxgpd.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtlszfsrfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsohlvobg.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtmhglyppi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtczuiffmv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gttnpzfjpd.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtrkmxeewd.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtqpmzcouc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtvxjhltxg.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtqqjrakwg.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtvdvkvmuc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtdmyfmfcd.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtggkcemja.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtoqfhgibu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtfigzbhxn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkyqbrky.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtglvxpoqq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtwxlyvdyn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtifjvftvi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtetiowmlp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtmpwumjsv.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtdajbqvyw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtnvfqijrg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtsbqtakur.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbblgolzw.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtdvrqvaoc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtahfjjgja.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtqxnmdnub.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtkfnfgwdn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtslmgdjbh.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtzcejbicu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtxqmbpdew.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtxmepqccf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtkdiwuweq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtepvaongu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtisptjooa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgnhwxbki.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtoqaaxows.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtiavnidno.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtnqxveuzv.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtnbbxgcmn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtgdnfigpg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtcyujaosf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtrtvleamc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtkrggcrmj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtiwikimyq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtzstqmyub.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gteauixgdr.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtutsmyzsu.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtsnbqfulb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtbxrttwbh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtwhxvrnnq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gtofndviin.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtptnkkpih.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtbncecddu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtcnayqwio.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtybwbtega.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtcsmpnksu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gttftjsvqj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtsdebsxhn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtzwtrgrzk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtocenqcfb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gtyreqblkb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtbxzhpbbv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtpzpbmaow.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtxrfbuawx.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtxnjixsvj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtztiepowy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtajzirsif.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gttbvqmtjw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtboivytdk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtsectqkhm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtuisfafiu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gthgbobfky.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtmcmztmpz.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtdxlnevxx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtjjlwlmxt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtmycxzdty.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtqnzbjbdk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtqvnwyzip.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gtsevizuun.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtcnpadcjr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gtukqjyrbc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtvrysawuc.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtjqanmdiz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtapcysnmn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtzdnoyfhu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtyicmynbm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtlfsfgovp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtyexjfbrd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtnxdwrmbd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtnxdshwre.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtiirggrka.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwgcgfnha.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtsupnteju.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxvadnrst.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtmvzhjyon.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtihqmhorj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplsyhkxp.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtwscvxpfm.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtjraimhnx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtlxxrsluk.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtycqrvyld.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtjuiezieq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupnqmnhs.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtulpumkgh.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gtwlypowpz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtmkwhwkrz.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtxdltxzvz.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtwwrcupgo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtwekuiaky.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtsgvqmduf.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthfeghbyz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtgbxjklgr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gtjlnezoub.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtdpendzcb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtyzzbogyk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtzipeeaqi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtkxjgippx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtryjhkjhw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtzaiiyfsi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtywrtirnc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gtimpnyflb.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtdzbeahuh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtvirmpvjm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtnpbekyog.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtedptekif.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtyknlojsa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxzipcye.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtwyhuuysy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtiyzyokfs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtnblrfukb.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtbaidldxt.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtuxotnxyw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gtwemaaric.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtkvjmjhmy.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtrbiklswl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtwubqbtsy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtpalacamp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtdtydrgms.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtqstmccqo.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtsziukovv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtwhwbyziu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtksxysgua.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gthgsabyrn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtkpuxbixa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtuycfoocj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtxoslqyrs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtddoyzkik.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gttiscynsf.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtdjarnckw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtrtmfiuum.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtbkpqcktz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtiyqtlfva.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljzpubsv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gturojnieg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtkzyblwkn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtyyembgjc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtvikjbvha.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtulmscdmu.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtexzpvawq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtvoxpklvp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtkzhohhnq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gttrkvrszo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtansfthpk.html


<!-- 参考信息 -->