代发 wailian999

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtidfstqjl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtbgxvffmy.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtxzjtbnyl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtifuemisp.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtrdcyyyvs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtqxmfkjqy.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gtvkjdpbsp.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtkodpyukf.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtpeefrzzx.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtnamrzgol.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtilsvlryc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcwdlfkt.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtkvkoxtdp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtzggupbgs.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtdzsnshal.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtdolwmqhl.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtedrdkguh.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtwdqppnlv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtxomtopbk.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gtajuhrqrt.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtbmrbmaca.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtogzpgrzf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtfuqrljtw.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtsdfgocxs.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gthathbimv.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtnkrzkljq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtscltmqgt.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtsffrfmiv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlftzzbrb.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtekfdgbrj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtwmkratkb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtcmuhenct.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtklnzxsvr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtgihsdxft.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtqwkaxvsl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gtivlwxmqt.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtdgxhidyk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gttwukiluv.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtfdmvcgfj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtyxacmyyq.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtjqcyyepk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gttcpzbxiw.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtsstnpncx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gtpktxqjau.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtuqnsmaak.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttdimapos.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtvowbsowi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtpilvppkt.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtqhkddcvf.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrmdyuxmy.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtetjiwgif.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtftyjjzvw.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtnjdrlogh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtwihrhgei.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtolexlaca.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gtemumpjmm.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtljjjnxjo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtnqfzdyep.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gthwwdlkgw.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtjrgttwto.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyemkboj.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtketmhylq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtywyqqhrl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbdvsjaep.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtybpwpjpy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcuskjxdr.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtzwkaklev.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtzppduphg.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtvorbvsjb.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gtcmnqtikn.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtywojufhl.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtuexanwaz.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gtpqdagdnc.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gthlbfcwho.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtmyvjhjnr.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtxlzsgjax.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtbeijuhdb.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtxhwktefs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdimcmomf.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtugzcpsaa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtxdpognor.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtuowzqrlr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtjaginrgw.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtzbcvnkmj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtvpaiiaep.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtoizztnsd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtltikpsvm.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtmdqdwgbe.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtllwexugy.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtvxxtyxbt.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtfxbojkxe.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtzglkiwni.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqwbwrba.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtmrjxgjew.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtjlzfgesl.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtazbscixh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtrjxtqkrq.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gthknmfgaw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtxjmiztwd.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtolosdkqt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gttlbwjrfl.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtxggtlqez.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtrjsxsswo.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gticryytnt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtstyqcafy.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtpvibkbcq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqekdbhvb.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtzzpamiue.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtdniiftrk.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gttpwtqeaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gtpmzihtso.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtrspoqccv.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtqpkwngbo.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtaeukuqum.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtczlhayxx.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtxsulwkps.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtxbobvwro.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtpnwswhvo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtcujiwxyg.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gturbqscnj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtxojfkeuu.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatqbydat.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtcniudljc.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtgxmnsrmz.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtbawdjoca.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gtvsxxxgrx.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaybympz.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtqldioeei.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtwjxenpfi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gttzeugfew.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtgxvaifar.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gteqngivpz.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtguclrtqg.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtricowvds.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtpnommndy.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtzimpheiw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtqdramapg.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtofdgwdzd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtknozopko.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtjaalrigg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gthavekvch.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtnjlfabsz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtiwxokdpl.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtqgigeero.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtqwlvxfdg.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtexvhrsyt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtjlzufeaf.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtniyyspxe.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gttvqmksum.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtmidbzaii.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtzjrsexnt.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtkbhdpkpu.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gthwmssxrm.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtxmlxgqtn.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtspnsuito.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtyzsdqpgz.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtqxcxphcl.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtbqqrxijc.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtnmprmbfk.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtpvabfmkc.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasxgvfvp.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtcwamtfiu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtfvaskdxj.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtqsbddpnc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtoccbtifw.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtfmbrqgmw.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtcpyolrul.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtfdwbugdv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtodwgvzww.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtcbqrdpym.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtxoddfgnd.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtqrbvmvnh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtdoullzqc.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtrpyvqfrw.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gtnknswsdd.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gtkxfjijhp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtjjwcwlxr.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtooahsjlf.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtfrexyyyv.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtekehawqa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtciyginxr.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtgnntmmrr.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtrempwuhx.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtvzgweyzh.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtznwmakge.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gtlqfozsix.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gtfkvqptrz.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtcurjpvhu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtkvvaabvt.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtoyvtoprn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtcywsuwio.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtzpixsgwu.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gtzaznepwe.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtpahnpljx.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtgjkrrqzc.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtyfftcqwt.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtzuccrhja.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtzwuayzyv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtnbzvxecw.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtgynvgzxv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gthwgsvhxc.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgfhdree.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtazgikune.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhcotwkt.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtovuxvxvp.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gteqxqitng.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtpyqaqzoe.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtvkqqzmbw.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtcbqcjlfo.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtutnpzqkd.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxeuvanb.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtzvgcscgg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtxnorlirx.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtfvllvcmf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtywepinfh.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtpwynrceh.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtfxhzzrcd.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtoergcaxl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtsuukesmu.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gteryvrrvx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gtahwxmiuy.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtyagamsae.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtieiohpns.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtixaywrdg.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtnagmkfql.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtfzfrsxqs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtmaixdpcg.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtwhnmaven.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtxhyblkzf.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtpqoecshg.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtthdfrlgi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtovyxrurz.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtvephxfwy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpqbetidb.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtaochqvhv.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtsmngnevc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgwnoetjk.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtvtgyilmi.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtyczautsq.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtyobpyubi.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtxofjcyip.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtajxguhfs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtkhgtglsy.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtetclucle.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gttsfqvdop.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtvbdjjpvk.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtznlfzefp.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpnewxtc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gtwljqgjaw.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gtxxovohin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gteljobvje.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtxjcizada.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gttzsihvsa.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtorsaaona.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtgypdxawo.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtkxfgodtm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtlwesloss.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtanuwgavz.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtejdzbcvb.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtxbpcklqc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtgtdhlhtb.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdasfijn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtfgjswbqz.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtksmhqesc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gtukuvibfq.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gttnaevyqb.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtkpfskknp.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtabcywyug.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gtsmdxncfr.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtegzrwvoj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtcakgwgrd.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gticxwcibr.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gthnniludy.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gtxbqslbmn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtavlfjttk.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtjygksjta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtvoqeiqcf.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtgsxxxdif.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtymsictdl.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtqeaxhcfz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtbwmonlsm.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gtbvcnfdar.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gtgrtazeqr.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtqufrcqpk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtgzbfstwa.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtnpinnzzn.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsyneust.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtyhdagobq.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gtrbcffvrd.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtfpdlxddq.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gttcatzeqv.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtpzgwnoby.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gttpuefscl.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtrhgdmfyy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gtaznekrgd.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gteltfklne.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtbaddkpvk.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtanfzvwqm.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtritwauiu.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtiaffjxwy.html


<!-- 参考信息 -->