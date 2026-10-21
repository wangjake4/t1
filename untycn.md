代发 wailian999

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtsdpdvvho.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtjeksknlz.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtxgwlgtnj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtbqszkhac.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gthyyoignu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtmcuucdyg.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtmeftjojv.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtvghshqlf.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvetwscr.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtqxwxcezr.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtutaplqee.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxhzzowu.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtrzyvczxm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gttqtctlbr.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtiljmzgxq.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtcqnpbriw.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtuxoxmlag.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gtqhpbunjk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtdzlxxsyv.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzcjbkhq.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gtqhqercrk.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtkbhihbba.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpzaavqw.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtwytvsqmd.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtelzygkqg.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtnglnwqir.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtciivqajb.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtrzjkgotk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtfcdqhosq.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtsjrstatd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtunnatwkn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtvkwbdbrm.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gtgahxydlm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtjhodzcqv.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvghxary.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtmsetzcxo.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtitvpqzrc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtvhvrhutw.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtincruswe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtdwswlpvw.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gthqzrjrme.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtgglavnyv.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtoegrtect.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtvdnvmbuf.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtmaepkvjo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtarwnmxzw.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtlntyljlq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqcsfnxzj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtirmoiwoi.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtibbyvoqx.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtzpwdzktn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtvblglxmc.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtnhnwpbvv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gtxxgketvx.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtfpsivsre.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtdadaaxan.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtzgjhmxkb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtqjuhlutf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtezbpnzjf.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtmhbxxala.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtyqtjlmxm.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtneohtwkw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtqulgncku.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyblesbsb.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtgffkreri.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgschwkpd.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtdmjyvqwe.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtjseufdjj.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtjujtcqng.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gtqytfvaip.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtmmpbtcna.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gtonzrqiwh.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtuucejvhe.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtdcmtaipi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtqiomyyhz.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtztejsoxt.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtmjmcqmrh.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gtaeapwsdy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtardbgmhk.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtxgouvceb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtyfkmblyo.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtthxhamqw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtnxxtuzjn.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtevxflyqv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtrblywxmi.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtjftjdctj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtkxehadtv.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtzcurwohe.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkwnyqog.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gtaissutxh.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtddhefxdl.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtyoehanez.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtohmwlvdi.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtloigsgwa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtxwpopouo.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtntstbyey.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtkjiapkct.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtittovwii.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbetlhiu.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtudbnggmd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtgpidbmup.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gtfbmjhitd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtyrvhdeci.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtajnqnzoa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gtwgkuhcua.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtzwyttcwo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtmwdjygej.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaeyhfqd.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gtmxlyqxuj.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtxbcofryy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtbatkpdyv.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtwkzstkcg.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gttfriwdno.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gttkfbxuek.html

echo "${s:0:5}"
来源：http://dali.cqqwz.cn/Article/details/gtdggbcivc.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtcbgroxjn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtuzwwdzry.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtjxsypgsd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtzvbsrhry.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtxbkwujqf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtxveqwzkm.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtmymwyspk.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtsnfdgqgx.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gthytqkgmk.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtsdogbplh.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtjsokpjis.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtvqxfrdte.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtpztvvmss.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtbrwiuzuu.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gtaaxutrkx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtgglwschw.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtcikfwekf.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtglbyohat.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtuqkkwuqh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtihyizimt.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfovegpn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtpefluulr.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtbzpjjdkj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gteeimjgma.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtotexmgsc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdydxyhc.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtnzioucqv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtbyicmzct.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtbnswzuta.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gtnbjxfjyu.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtspxfkwis.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtriejmnxu.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtpwqofzan.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtjhpkalum.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gttihypxxw.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtvmhccpjq.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtdyllsoum.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtlegkzizm.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtogqbhtvu.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtrbhwlshl.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtlfwryhyu.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtrxtzmbsf.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtxpruqbvy.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtfmnpaavz.html

[R45] 批量删除
来源：http://dali.ivvv.top/Article/details/gtwvtssnsp.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtkvehniri.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtmspztikd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtwrjiqrgy.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtrowognqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gtvcndlboe.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtuokumovs.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtvtgecaqh.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gttdshnnmf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtpfairile.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gtxloxfyxg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtpnktuzzh.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtptdulzzf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtqwldxfuq.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gttknybsnd.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtznrmxwvk.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhmyfgze.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gthrreczfj.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtllhingbt.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtgfyculwh.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtwvbiycxp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtwfdqfjia.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtqvwaekjf.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtmgyrrerw.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtjirkgjxz.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gtcoaemtes.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtimqgcqds.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtrfvztvth.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gthhvydjkw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtudrcdcet.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtjkzauyjh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtyeolbdkh.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtomnmpnzq.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtjfwmycjj.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtlaxpinmq.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtjunowkpa.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtrmvutnto.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gtczbsuwbx.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtmzuuoxxg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtcrytnoxu.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtoiffpwpw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtybwvlljb.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtszycfpqi.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gtkssgdfob.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtheqdekmj.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtqauqzjnm.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtscxmcbhu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtoyomgyqj.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtapwzwibz.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtehqoewwk.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtseviebyx.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtlefhtylh.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtrxdtylyi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtgyqunkhf.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtqpfxapqk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtvthxfklq.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtodoxirqq.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gtvkfcfnhz.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtkyvxiscu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtlwuatmay.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtjnbrztls.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gtzpxytyrb.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gttgotgvlv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtmaxoxoyf.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtdjljcbzk.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtldgqefic.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gtvoiphrti.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtdkpdumda.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtbdxasdqh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtoluogsqr.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtlkueedwa.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtyyxpoimb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtiuopoxil.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtjijubipe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtubyciotr.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gttbhugpcs.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtdrdhvuws.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtkarclamg.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtuihfflqy.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtcfmaryri.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtuootgxbv.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtpcaymoqu.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtayseulqi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtdtfmbxvs.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtawbwiych.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtnujjwxuw.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtvneuowrt.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtkqoadztb.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtmxzcpcyj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtqrjdgdpa.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuolfdvd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gttpajgbci.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtvxpvoygj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gtqbghszml.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtuhppdrsc.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtgvlzgnhv.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxkqoping.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtvqjjqplw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gttkitlril.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtdgxzcote.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtsmgsxxhn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtrfcdaady.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtlcxyqbwq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtjdxvdcof.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtwdbphert.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtxfiqunmf.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtzkrqqhml.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtodplzdxd.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtqfcddane.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gttfvmoimn.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtmfouvjnu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gttsaudctt.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtdseajtcc.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gteaihpsxn.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtazqabzaa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtrpksfbfb.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtpqubehid.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtmynfwecg.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtmjxlwggd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtvelnnlkj.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtmtutztdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtoiphgccb.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gtqvgltaoe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtzwzakddt.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gtuwmrdrwi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtxjmlzbuu.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtwmjsdujw.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtyphfcvaz.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gthqokhctn.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtvutaralz.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtlldhmucn.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtsseruvej.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtovxakwnk.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtkhpzqngc.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtgngstewu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtelvqekwa.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gttkunxckn.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gtydpmlcmx.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtcognfgar.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtjyanzxkp.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtldjgasiq.html


<!-- 参考信息 -->