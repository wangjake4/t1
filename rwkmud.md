代发 wailian999

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtzdiduigd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtnzlcdpbe.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gthiuumbhl.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtlervcnvv.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtpuqrfuid.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtiuyknuav.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtfofytdhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtbzuipvnh.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtyjdreesz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtmwkoxcqi.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gtfwbjnbug.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtsdulbdwx.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtvszdebhx.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtndelqxku.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenozyhql.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gtnjzrzflx.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtcccayakv.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gthdikjduc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtctoucrvg.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtbrtwyxti.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtorgewall.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtoydbteaw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtmjkvabbh.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gthrfsixfn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtefhyolou.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtdgcsmszq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtqnkkuksk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtdsxzvwpp.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gtageeiyfg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtahdpfzpj.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtcmawsgxi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtndopswqv.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtysgmyeej.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtjtujtamm.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtdltjldef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtnhxvghww.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gtzaoxopjv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmwrzohvy.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtvykcgvcc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gttulpsufy.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gtxzjxmphm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtfgmyzebe.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtncbuesfg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtftfwkvjh.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtorqzllbd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtvcmktyjk.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtwfrrmong.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gthateqggf.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtqfnxbvkf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtvfshibix.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtbgezbdzj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtlfbsphxf.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtpaqtpemh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtclhnkleb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtiqsvbfvc.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtzvcboook.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtbcvfuspr.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtelcmsylo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfblmogex.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsbygdtpt.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtbyerumuo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyljlmffm.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtcpblprgm.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtedywauix.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtarlxcgos.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtunjezriz.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtvdmhexnu.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtzjdyvnsl.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtfdiewony.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtwrzbyebe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gteejffvvz.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtsigeuwhq.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtoummzobp.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gtdnphglei.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtbgujrmkd.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gtiydbnbtq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtauibrmwb.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtefqemgqk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtdcnbabhy.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiafxbuwa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gteckfyzox.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtvhfuukkt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gtltxznyyr.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtsxfpuroz.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtweuvlswd.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gtmgehecpg.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtgnydmxqm.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtwmmkzwwq.html

esac
来源：http://dali.birdmap.top/Article/details/gtotqielil.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtiflvrnjz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gthupcxqct.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtpoxigwwr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtprncztwe.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gttyxnoibm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gttotamprs.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtlipjcblq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefribeqv.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gthjahoxzs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtnefqwevc.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gttzwzquhv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtdiwvmwgm.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtvkwidkzk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtekgmmrku.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtwmauielz.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtlibupbry.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gtxldkdqlj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtdbcktfml.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtlbhfplto.html

echo "${#s}"
来源：http://dali.jiagoushi.top/Article/details/gtqawpiqod.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtszzcijtz.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtulxjiulb.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gthmcbkvun.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtizvufrdo.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtldjjkyev.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gturjathxd.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtqnvohrge.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtjiawactc.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtilmpikol.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtbupahfmt.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtisljqpak.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtrzlfettc.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtiucdbrcx.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtegpdsxoj.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtnjdirpxs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtiqkdoqch.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtqrcowpdg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtgulpzvtn.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtwetmusns.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtquekawgh.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtmjzqrhux.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtbqeowbbq.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtqmamybuu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtoglblhur.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gtlmwiyjcf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtdkzuapeh.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtbgvmktgs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuetiantiany.cn/Article/details/gthexwvrjp.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtclhcrfne.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtltngeysb.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtyemfzsbp.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtxummopzr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtulejeasq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gtlvdxtsry.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gtzgnxrxcd.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtrhozvxuv.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtcxxmuwvt.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznnbrubb.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtlrnnytjg.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gtjmvznfmt.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtomznbazn.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtxmgumhzw.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtrcpzbgit.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtihaxkupk.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gtffakesfv.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtbrteqljb.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtigedwjzr.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtbaxuonsj.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtcczbbbjz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtwuhqyodl.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtmlmepirq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtcmbvedhv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtdbbokyba.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbigxszc.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtjczizqjr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtbknivlcr.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtrholvqqz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtxgpierhc.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtwydblngw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gtjxudvlpf.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtslmffpoh.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtdrkrhnlr.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gtdgfzmhml.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtmittblbc.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtsxckdnvp.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtgypsmhqz.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtupmawksf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtonqxyaau.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtooyasrjx.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gtqwqccmwi.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtnnysmifk.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtgzkdpjqo.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtmotdbbok.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtkuawtlts.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtwlgexvbs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gthnwatiad.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtunkqjdjk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtyokotsab.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtnyjrypxv.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtdhkbzxnv.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtqcfczztx.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtjdxbwkmd.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtocprydls.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtulgrfaii.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtzjzzriph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtpponkboz.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtlbiaycla.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtrxckdqvt.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtabtmlmxy.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtwrfxzkpm.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtqtwikvzm.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gttvrmulyl.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtyqsgpihl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtoqqhvblw.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gttvhfjwwa.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwcpdwmd.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtrvudsuyl.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtlccszxar.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyawojdq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtsrrhfaqm.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtvsfpdlxx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtchqvambc.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtsdgunqjp.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtivqareay.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtzxxfweqc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtufvmwquv.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtmzfrivuo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtqprvawyk.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgdwelkh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtjhfmhfxq.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtzfjhlsze.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtzobkjlaq.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtgrvtjmng.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gthmnazhvd.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjlegaoh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtluhpwqge.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtyktcqhci.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtwkrkhrne.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqcefqgpv.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gteyefodfr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtffxioolc.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gttoqegumm.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtuzvxpqxj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtcgfohlnh.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtdqyruizg.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtcjmzeddl.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtcwsxxifi.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gthalumfec.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtbadvpajf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtqdrjqbqx.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gttyvawfpq.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtgtqhlcow.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtkycoyebq.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtbzsxsbtb.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtqxkcfvhh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtpnimlokl.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtrafatmmh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtcadgiyod.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gttwzwdpqw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtwoupucqr.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gttwqedkuy.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtnnceveit.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtbjxzdebe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtutxxrncn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtjxfnczwc.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtsqgustos.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtjazktrwy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtdbuspeto.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtenadawgj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gthufdiiem.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtulggnaaa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtwsmvrgdm.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtzfzttlwj.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gtuihjjvbn.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gtaukclyos.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gthgjttqcu.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtvxdwotli.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtmfswnrjk.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtogqhllyc.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtsngwuizg.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gtwulommuj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtnacrbexm.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtoxuxyvhp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtdqdqxsql.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtukttovwb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtadjctola.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtdgyewwcy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtwcykpwpz.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtuxhrhnjv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtbjkhmafl.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxngocwnb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtlbrxaupf.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtvdjicumc.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtyvtbwugp.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtieqcgpyw.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtonfeuxcr.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtbdhvnzpy.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtolanzvzg.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtbdpntgnv.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtzlqhsfuy.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtiewjfhly.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gtgcathrzy.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gtqpxyacoq.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtvqihiqth.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtvozjumsr.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtzmctelkj.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtacubjjrm.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtycaxwlmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtzsifysgk.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtrymdocgy.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtwnebzebw.html


<!-- 参考信息 -->