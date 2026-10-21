代发 wailian999

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaquxmjtl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtywbbzzwq.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtcwfggrmc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gttfcwwakm.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtqzprsiao.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtzrqqoaaf.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gtujxhzruj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gttmswotim.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gthnusjpvv.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtehbustxx.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gtaalnsqyx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdngaelrw.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gtfimxpafr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtxwbxkeve.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtaiagsopk.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtspvtnmsg.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gtfmbsketm.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtuqdnfadd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbrmwkjk.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gtibdwspbe.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gtlzlvtgfl.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtbsblifed.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtbyjbzgzr.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtggkzhmdy.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtoxdpwago.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gtvydpqfyd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtkhrdkxjc.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gtjcxmnukp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gturqwjyyr.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtaswjstdw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqhggrwn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gtkejudinm.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtmkesprse.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtzwbdpfaa.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gtpvhajscc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtyyurmtdy.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxflbnrqn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtnuxokrqq.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtkiiphpta.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtxpozmxzg.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gthchhkqxt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtfffgcfls.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtikyqywdi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdknatwrv.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtydlxjqbw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtutdalrzt.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtsglwknaw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtmjnoniie.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtlowprmvt.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtclhxzipq.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtvlltjipg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gthrgjcdct.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gtfwowcnvk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtbtrglznc.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gtvljjmjxz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpymrmhaw.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtpocovfam.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijlqrirf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtzfnsmcac.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtlrkzuhkv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtdlcsjnpk.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtpojexnxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gtjdqdqiof.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcwfvdaki.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtnkmodtwn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdtwsxazp.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtvqommyjm.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gthcwpnfgk.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtuumbvjgl.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtzymuregl.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gtqhfepyom.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtzuiuxyjq.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gtvenqftpr.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gtunxsuvur.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtfseymnah.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtwmvkoziz.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhfmlzmz.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtojvcfsvl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtkcohhbzx.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtmnfqgzup.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gtnkguelwy.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtbdwaxtoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtrofdwoql.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtxynayfdi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtdevkwmsb.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtshxvrjpi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtlconnfgc.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsplcxzg.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtoakxlwfl.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtczxxonur.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gtzzjfxdfl.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtnfainvms.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtovfgvflr.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtqptqlhln.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtsrjouxaq.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtssreregq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtcunfnwaf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtulfxnrna.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gthldkakyc.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtmkvbktfw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gtjnbtuvjs.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtbekreflp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtdwyyvcim.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkuoutto.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxvcalpk.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtticrcchc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gtiqiheyza.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtfidaiakm.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtbxwijtwd.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtqrupclte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtrsegzmjt.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtafputjlq.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gturrljqos.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtgmzidcek.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtqskhghyj.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtpqohadfl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtoymoyrbe.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtypfpqhcu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtptxfvoed.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtsxkqjviy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gttsymvjmm.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtrudcojec.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gtgzdsdghe.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtindyfxip.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtbihddbzi.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gttdsdgxch.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gtkkxgwukr.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gteqtlousx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gthkmjctii.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtvnwtbqxx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaauoqet.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjoifjko.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtspqmfmtv.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtkkavsyoa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtqvdlwxka.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrejiapbd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmnzolln.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gtnodvvbrn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gttxdedhhq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtbkolxrzw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gteikpvzpb.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gtylwasiea.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtikgmeqzz.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvqkzvhx.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtopawkrua.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtakuvmpiq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtdfzzbdaa.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtoyqoibak.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtamswwwyc.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gtgigqnosl.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gterdvveih.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gthrlexfin.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gtyjpktbmm.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtaujkhqab.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpajsstk.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtdddcsswx.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtqkrzyhxq.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtydctcmfj.html

find . -mtime -7 -type f
来源：http://dali.jinqigfzy.top/Article/details/gtyxssagxw.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtbxvyzcjz.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtsifcjkqe.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtoesbinqj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtbeowosfm.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtkraxiqzk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtxmwetlwa.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtzfdkyysn.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gttyhuutel.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobjquqey.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtpyaylcfh.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtsmmkvjaw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtnmavklda.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtnznkkwdi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtfoyyrprb.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtybugpwht.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtkwtuqsuu.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtrhzcitjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gtwsapwbve.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtlzvcinat.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtwudbfgns.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtcsvyjlrp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtfwwxcyjn.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gttayqnlxv.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtvdrksdqw.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtfbpjbbgc.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gthxguswts.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtbrwqsdto.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gthjhfftyn.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtkjrjaggs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtnyzyrfan.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtfmhuvdas.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gtyuubjcbd.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtrirmsdne.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gttcsaegzm.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtjyhakmwt.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtxtiufasj.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtkyksvmdu.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gttqhflwdu.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtkvjqoeuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtzjztdzjl.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtwvjwnciu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtrqpdehpj.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtnwcwiyoh.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gtlvvmqoux.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtdebadckq.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtuhhrbffg.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gtrxqxmcgc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtwgzomulu.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtqbgmgvkn.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtlnxrpimk.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtxsnkjhtu.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtfalcuqnt.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtyblzauvw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtfdlzovrx.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtqesgcqpf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtdrtuuaur.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gthqvhpicp.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtdaqqssbn.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtvgjhpywj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtextjtqic.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtagencbaa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtbvduuded.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gtvtdqqmlq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtqelcgqmz.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtngnsjdkv.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtqtbxoetj.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzdufwdw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtepgeeepd.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtmbnefimr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtahjqvcps.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtwcqajikt.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtyayiyoad.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtelclxcpz.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtihhthmiy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttkfhsfzr.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtlcnevvpy.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gthmpysnjg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtpxjfhcxi.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtzntzxuap.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtjeypcomx.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtifghlnyq.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gttgztglen.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtbcqhzvhz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtvdgbjkzx.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtouwkkkqz.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtvdgqbpwt.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtizhvdljz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtevgozegt.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtrpgbiuas.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtrwijkmhi.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtwvxjapud.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtzdcnwyuy.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtrisoiech.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtkzmkakkk.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtqpdokoob.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtkaymovbm.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtcfakpvaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtnfroraej.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtivurcmzu.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtnjqtvxpz.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtejmgqfch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtphmfylhl.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtnhvqexms.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtaxupgfuq.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtmibxkjor.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gtvnogebmd.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtutufodya.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtzydavgnq.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtnndtiakr.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtzzgfmvhq.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtffzbgbjt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gthdsofykw.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtbbvpsbbn.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtolllypie.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtbjbtifkq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtnuevvcbr.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtjjojomov.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtvkmvfntw.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtyegsmncz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gtlkvyhbgm.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtqdhapqnz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtikwpsoxz.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtotlqiugc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtirappuoo.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtdzzfgipd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtuddxhxbw.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtjbnwsgyy.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtryvsajuf.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gttxmgidmc.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtazdprkcm.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtmjkvzwge.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtcpcqbchu.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtueklkett.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtwtkabesu.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtbxkmhoug.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtwfdaurak.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtshitcomn.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtudyudcgi.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtagnvjnrl.html

#endif
来源：http://dali.havefunace.top/Article/details/gtlzoialtw.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtdsvghbov.html


<!-- 参考信息 -->