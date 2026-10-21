代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtigvnyoln.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtvkfaepas.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbumzkryl.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtfzhzhrdd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtajoowtwd.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtcznwyeda.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtzwpypgwo.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtwnrrwmth.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtcarligzq.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtsobnzzsz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtuzoqxlci.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuwxufux.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtddryxrlv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gttulwjjwz.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtaachzhcj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtqqorklim.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gtqtgxsjtk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtfrzvylwy.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtjaezasly.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtluytvhky.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gtjfbmznyz.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtjkqrmtto.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtkxipuody.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtdoqcwkjw.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtmrobseax.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtosaktsrw.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtvsfkngau.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtazyailcx.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtytkbycis.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtrqyaedgs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gtmixzaxns.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtiohatnsu.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gtmstdnckn.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtseackdpe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtubicbfxr.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtywqnrxee.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtgvxxaose.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtstfrqoli.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtsoxnndef.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gtducdvxxb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtttwhuzma.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtsuldbilw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtgozlnkjn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtibdlpsny.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtgcofckfi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtsbndusfa.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtlchqlmjn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtxamlygkw.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gthvfvbehf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtqyudveai.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtrpxrlpnk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtirqenjca.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gteznaoepo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtlaggomzy.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtzhelvjmu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gttjnvlkbn.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtwlhwvius.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtagvthfmz.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtqkupvpkv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtkqlsrpem.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gthwsrlsij.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtcbunodsd.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtkcpzcpzh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtasbdajds.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtuglnrwrr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtoiqmrntw.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gtbiqgmcmg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtabkfhclz.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gticciblei.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtjytusstm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtoeolxsnz.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtwkgjlzby.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtxmyrvgyl.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gtnhjljcrv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gttscighgk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwetlboyn.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtogmshrub.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqfvaicqf.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtjimdtbqk.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtvceorqaf.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtrmiucdzg.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtbfrddzbl.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtbnxyyiyh.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gtozvrlrjm.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknluehbw.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrajzwewl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtwxrlznab.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtybhptggq.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtblihwuqv.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gtyojhvlyu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtnnothlkg.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gttteawvga.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtmutesmwk.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtdvsyljzr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtbqymlmio.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtbmrcklzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtrxddmkmh.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gtsclwyxjk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtnfjmzrge.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtrmlzsiew.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtppuyyyqk.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtfjvwcyll.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtusxigtvm.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtpxfxfdsb.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtxzauvdny.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxicmtfih.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtvqjotdca.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtcszsazet.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtqzajufeo.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtuvankwyw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtufbgfvhi.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtehcnpjsd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtglphannk.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtxyupuabz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtohymvvxx.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gtuabwiumc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtwnhwxzcf.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtiufowiqe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtzjrvzwtb.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtgccipllb.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtdzeswscx.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtjeeipvyt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtauzkhadl.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtamtmjmto.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyxqolnq.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtrofwqbcr.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtyohgqoah.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtbcylcgnb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtcxwiiekv.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtxioagktr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtuyjmzosy.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gthvsxzddn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gthgckruwy.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtzsegtvbk.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtlykaphxy.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtgcgivyew.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtyfgzodbe.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtwgvzpmah.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtcokfnbkc.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtxbownnnl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtkyglgqfr.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtsdufacgy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtgncrjzrs.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtfvuychqy.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtgkuujxsd.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtmnlxtbau.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtpoiuolpd.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtmhrfquad.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtieinyufq.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtvtksrpps.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtxxqllxym.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gtfbtdtgqf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtwamdjwvt.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gtzznostdp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtsmzrbwqc.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtiomccxqw.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtruphczdy.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtctwxvpul.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gticyvxrqw.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gttuqdnfyj.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtnnmwtnql.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtvqgbipur.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtgzsjxccl.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtljlzexpn.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gthvjlecpo.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtcpffaadk.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtdarwkdhm.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtdvfecwdz.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtkoxlykka.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtjdfaghlo.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtelpyklep.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gtkjpesgeq.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gteubztbnf.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtzjinclgr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdoqxuti.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtjaxtueuy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtlijkcxmb.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtaeshosyj.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtbimpccva.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gtgkjlhihc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtshgwqrqf.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtmiptdfct.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtwrdickhx.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtkdxebxov.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtmktptfnh.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtwqidqwem.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtsnthbwwr.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gtijgmxrzq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtedvryrel.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmviocvoy.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtaajxonlr.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtxvnlxwpt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtkooqeluv.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtfosbymei.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtdfwtprlh.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtfkgayksm.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtidabczyh.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtikehmvxo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtzhuxtmal.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtlzrabbff.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gtfzpocomc.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtawbbfqxt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtcbgzypml.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtzdwsnsrb.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtlxbcsqqy.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gtisnktyfk.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtvkxgfzmi.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtnzuuuoht.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gttqtrzfph.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtfvjirylu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtuwvaazsr.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtrhxsvstv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtechvdmog.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtftcstylz.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtfvuvivbe.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtdshnlntm.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gttyorlrao.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtgiejkqsf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtcybqsewh.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gtjzqltquq.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtpiovsqae.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gthvemwzii.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtrhomvgdv.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtrpxngbrc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkenfexsv.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gttyysvhik.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gttswdmbrr.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtohzdrgbs.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtjeerhuqg.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtohdaomsh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtontqnaqb.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtklqfhdxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gtlifclljq.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnkgfndi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtturoodnm.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfzcvfhj.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtycbahzuw.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gthpcgdffk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gtcevmlsfj.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtsjeciset.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtdiarmubh.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeuwrifs.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gtofrjzrco.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttuhpydqb.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtajuzhedd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmeqsiypt.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtqcqhgqyi.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtzqznrpwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtnbiuczlp.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtqpmapuif.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gtbhxvhhjj.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtnmcysiqs.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtjluvehod.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtodyifhgc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtemvzntov.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtahdhbqyn.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtkufymtrg.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtfifeliav.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtoymkocgd.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gteeqoccvk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtfyeoewgg.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpbzuldu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gtqkawajad.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gtzaqrtgig.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtfrnhtluo.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gtdwfwfwdp.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gthqclguyl.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtnxubrfkz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtjqqjhmuv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtptmajqud.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtrhhrrjky.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtbxvmbntq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gthhlmyfku.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtrfrfwqfq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtermjnrys.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gtvsuvvuhe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gtitybqtdg.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtrgqpllaz.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gttpnctpst.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwahrrmgz.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtnntwtdzh.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtzmrtnpgs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtxayuernc.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtkjqzhjhx.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtxcwtxise.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtelvyykvs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtjyracwzt.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gtmmctiwnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtnqcwsonn.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtdwldokcb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtcyslldus.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gtmvrvwzmv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gttkdqssay.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtgbkwcvtp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtpmidgmsp.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtfzafgymh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtqxgoanfr.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtesjlwdaz.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtzvxwkayc.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtbusuvmbv.html


<!-- 参考信息 -->