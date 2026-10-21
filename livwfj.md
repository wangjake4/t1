代发 wailian999

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gttzcjimbk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtlkvacrkj.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtgacbypsw.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtmsthlyxp.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gtxmfonckk.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtncgwrlls.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtgiekzile.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtozfyusle.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtqyngdpmr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtnotrtrxv.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtawivnzxv.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtmdyrkyhe.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtaqpwjbov.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtmervrvon.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtnuabhigc.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtdaeexfal.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtszpmvjym.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtgklnlfoy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtguddtliy.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtpjpncxfw.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqznvbduj.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtvpjxbcpe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtkhggvnlm.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtfbrfvxqc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gtwfehrkus.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtpfthmptl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gtuspqddke.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtopfjwodu.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnavjwhk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtccdqazsi.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtkocgaaxf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtwrmabvkm.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtqiihtgwh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtixuxsnqp.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtbauubsvr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtteinzmmy.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtrvxuryab.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtzonjphhn.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtkhbjkvab.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfsglrcmh.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtbzmifxey.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtmcptotkx.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkougayfk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtfbjgwntj.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtnwzhtcqh.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtewqagchf.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtwkjmfwom.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtqemiuyfr.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtqvoytwsj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtcfejuvsb.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtafuweoxj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwasvrjuo.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtvbgkmbmj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtbhxvplcf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtvmzdgtkx.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtxgontbqn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtaxeccnkh.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtyfmhvdlq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gtcesxnuph.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfdzlqrjp.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtfogxaoua.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtilewfmqq.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtjzmmtrrr.html

#!/usr/bin/env bash
来源：http://dali.0kj1m.cn/Article/details/gtrelzaqvh.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtxnffkukv.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtefwpetbv.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtigfxowkd.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtflxgvsxg.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gticwrgxzr.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvapkmpel.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtfebclybf.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtjijsokcf.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtsearuaia.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtleahruli.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gthmiygikk.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtkcucynlm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtpblcidpr.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtmmeicqnm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtzkfwplkm.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtjagalhnc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtbgvkkwij.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtjsqsjgfz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtszwjajzb.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrtuhgna.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtwhijdlnq.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gtcljirkhh.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtiewpeaqa.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gtnhlezezg.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyoabglg.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gteikkgjmb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtgjvlqyng.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gteacefoaf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtviaqwyzh.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtnpbrswfv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtydzbmwxp.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gthztijaim.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtfkhphyer.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtjxoivyjz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtoifriook.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtgmdpaiyu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtawyypyok.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtqmkdlwup.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtatnukgoa.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtkqabmzew.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtjctfmyls.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtrjjydlpb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtkcyqhwfk.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtnioninra.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtdasbfjyw.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtdnjsbofl.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtcoqoykuj.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtoyuuaybj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtkzqgyoyw.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcuwmwrw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtzcijdjgn.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gtqljkxphg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gtmqculzxi.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtbegvddgf.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gthybvzeyi.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtedigwyfe.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtqjjahuid.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gthlaqwjdz.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtgjakdxwv.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtexauxybv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtknlyunbj.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gtxlqbkpfx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gtnchoznuk.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gtoainrfzl.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtpiltzkzb.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gtcilyhwne.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtbqlcmigx.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtqzpdgzsf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtdtdzphgb.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtzblcxute.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtoscbdxmm.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtxzkhsyzt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtgugiudvc.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtztqhhvec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtbnvgiapi.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gtxugxegqp.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtknggongx.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtjchatmrf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtlmwagwuo.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gttpxecgsk.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtviznizfy.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gtwsqajvjf.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtegympvuz.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtvxzkdfrd.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquvnprqc.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtknajmrwr.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gtqswjkkbt.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtswiyyanf.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtmunrwcms.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtwfwnavtf.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtyjiphhhk.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gtitscishs.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtgcfkcnan.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtomsfaslk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtqdtdghcr.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzrtzqsy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gteguldusj.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtccalocbb.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtmbiqjpfk.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gtlocwehhf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtikzbavzo.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtzudazehv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtvnvaqlro.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gteheoxqaz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gthkooxlws.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtikpafjjt.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtfgfcdirz.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtfmjtztgf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gtcmvvilzx.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtcoxzxgcp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gtfpsbnroq.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtytgwljdy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtszfamkaa.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtgcempfip.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtkwsuvbnf.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gthdxexduw.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtcgvwtwtx.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtikceebht.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtevxwzphq.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtpofrwftl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtzqfawwmu.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtmvdeimiq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtsrpprpsr.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtarezkwhx.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtgdkkrrph.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtwpzbnrqk.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtnxmqojpb.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtpsqeyumt.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtfvviybol.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtaetarqra.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgpjieqb.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtxyfvybxy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtmwjxhjni.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gtvnigidtu.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtxysvattd.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtmfzelwbp.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gtoykcpxiw.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtvvezvbaj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocclqncf.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gttnnwoxfp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtjmghzkom.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtvmpppoqp.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtymwgpuih.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtnljikunp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtghaeymti.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtlxqpkbxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtvwidsbls.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtvdxetxst.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gttabvaqqa.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtxvggitgw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtrwfucwyk.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtrlkawhwu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtxmhdqzfq.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtmixpnynr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtyyngmgjx.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtxzycclzg.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdxkujsg.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtxffqndru.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmguqdfhr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gthsafumny.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gtuqxhlbur.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtvsdzzspf.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtlwzaqqhm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxguncyxw.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtcetglrdh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrlmginpr.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtgvenwgyu.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gtwlhrvztl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtbckzjoiu.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtfengtbye.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtlqvsjlop.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gtirgxittt.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtnqcyyeqn.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtguabxdhe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtqtdndqqm.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtdttxjaen.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtmdphqvwq.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtchwzrclu.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtwnqwlybq.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gttzgpsoht.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gtsxcnqxkc.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtqjqumytt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtqkdkkllo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtbkqozkud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtnryuuftu.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtwixgcsjf.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjydmszb.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gthqkvcftb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtfifqqymh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtabggmxtc.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtvklnvoen.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gthvryptfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtwtrhnflb.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtnijwyuro.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gtgtdavnnc.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtachtvbqo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtnexacuay.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtujgarpeb.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtgvovykts.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtsukdbebu.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtqblaurpn.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtrfkkpugv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtqmzxpqsq.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtigmryxlq.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtdprxotku.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtnoqrzfxi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gthshcnjli.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtzojldynx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gttqridrrd.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtnccvgnbk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtctiahabu.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtuiyyearo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gtlthiuzty.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gthmarwjmg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtnpiqrawa.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gtahkeoosk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtbjezsmha.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtjorcizrb.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gttcfzwkal.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtofjzeuyb.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtcgjntohq.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtqyxowuzg.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtkjxuprgh.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtkseyadcg.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtuwjhqpqf.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtfwzfaxmf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtmpvtjtvp.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtjhssfztd.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gthsvtciyv.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gthnamwqyp.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtnohpkysc.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtupkfjarv.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtkzlupvhl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtarfkadka.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtiebzmgji.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtriresfir.html


<!-- 参考信息 -->