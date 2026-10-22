代发 wailian999

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtdsdqccad.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtbwhdyfui.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtowrneljm.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtwubvhywr.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtceioztfc.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtfawdhnkk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtrtxkwubs.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtqotkbxqp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gttnibadmp.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtqgeuckkc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtpfcqwjgt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtnlndvgon.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtiwpescxs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtgxjorpsp.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtkzamqypw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtabwjjmqt.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtxiniuiav.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtpvfjxrno.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtpguwlalt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenlublei.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaujbedwv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtfvbldzxc.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtqgiltwbj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtppctallw.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtuuyarnwl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtspmvlwlw.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggudpyey.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtqmvbeahl.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtltdfoezm.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtirwtnwtr.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtcnstqotl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtociykidc.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtbgbyciql.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtcvhsonbk.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtpbimqxbr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtdrpmstps.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmiudwpm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtktqurpgd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtkqcezrik.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtsasvtzsw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtxqdpbxok.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiwwevcx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtstvbpgin.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfnehurtd.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtxiunpgpx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtimpfvdai.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtvylgufch.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtfohoewqe.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtgeyicwwx.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gteixctpha.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtszcfndlz.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtfwcyenfl.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtgpcewrhi.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtlrrigjwg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlbupabn.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtmdcbzfkh.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtobrvdkly.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtzmsxixok.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtjcixtlnz.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtsvakyxbo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gtklpnwjhv.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtuvaoabfm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtmhivkxpf.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gttcltuoua.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtuidvwvkg.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtatjkxevy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtafodlvnu.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtiwloyuyk.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtqsvgcibf.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxyuacrz.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gtexedczbc.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtzataohcz.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtrpyqyfrd.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gtcnnxldbg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtrprekpeu.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtwdcwrdjc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtxyglbonq.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtochkyute.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtpruzduzh.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtpyihonne.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtwhmjepvg.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtexdsptif.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbznpclko.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gttghlbcmy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtxqzvrvbf.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtgvjavxdf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gtzugopyrq.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtavoczluh.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtacbllpnh.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtpljnzhtq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqlexvmn.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjhyrqmb.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtbmsqbtui.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gteywagbnr.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtfacwvkvk.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtmrjfsoly.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtdrquxaib.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtnhkfhwty.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtrqvtktxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtclhfrquj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtqgklabiz.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtdehzngid.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtylvczceq.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtjvrhhdzm.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtdnclwqtk.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtfiquudku.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtdhifhust.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtnkwuippo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtowhwlvbj.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gttgkdidlu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtmzamioda.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtemhbzspk.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtqedgqiwd.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuhcxokz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtheflaggv.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtvypleqnf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtgjmtgpzl.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gthjlbjvek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtbfspjzyk.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtxcehnraa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtchefodlp.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtzsxhkzuv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtkdhzyics.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtuxldhxfh.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtpuxoadfs.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gtamoclwuc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtfyvszywq.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtmbdljhmg.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdphbttb.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gtfomqfvbp.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtbxlaclvu.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtnkzwybqo.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gtppgpuuws.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtuwkckiyi.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtdhegydpl.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtnqrhgwww.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gtqpnhysju.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtaienyipg.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtwusevmzq.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtenyohajj.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtdkxdkthh.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtmbgtifja.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzksqhlbf.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gtsebvhdkf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtrnodscuw.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtgpzvrzkb.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoidoanbm.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtakjuytyr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeohiqaz.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtngvsfmef.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gttmydjfrp.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gtpioxbxpa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtxnweqfep.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtunydknuk.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gthplrsotd.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gthpogdpmk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtjbyacvve.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gthuuaymdc.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtamyhgthk.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtgwpswdvw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtyytkbybr.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtburcqrzj.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtmhbomzir.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtxzpqhzhy.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtcwkqvwqc.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtyarqrkcy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtvyusaama.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtfkzwzvnm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtzxkmnfys.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtcmseadho.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gtqdeuorbf.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdopisepw.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gteyhaoqnr.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtsmlvgcei.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtzndmzxpw.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtxxflctqb.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtbqcbrwdg.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtffkuajpj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gttdzlwllc.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gtchifbrem.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtegphvblg.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtlubckohe.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbxerzek.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtijzqzvyc.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtkzzpvpmd.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtgvuhyqxy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gthkudrnca.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtudozfotc.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjwqreqo.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtfzjmnjcs.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtnlybgfym.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtshfdfqzn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtdrtfjoao.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtobealdos.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtptbhseud.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtmsgxyhqp.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtgehudrcr.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtqmjjisfo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtwmmiloez.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gtwwgjfzhi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtepwbeqwz.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtrtrltkku.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtkokhopuu.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtrtvkubew.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtemeupljx.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtiijsixvs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtnxxmklnt.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gtessrolzh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtsbfovxda.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtojwfjiwx.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtatbftvke.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbigqwwzu.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gthcupetjp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqihwsqqe.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtdhocsqsy.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtufqaqets.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkhjsxbtp.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtofnykwqh.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtybwdehlc.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtwzowgzrw.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtreohonbk.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtfdqaejyc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gttxdyqqmi.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtqmbinvns.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gthnxqmtcj.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtohfxjixd.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtlavivwnr.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtqpqkvjjs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtocetqmpe.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtddvfhkgr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtdcurtfdt.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtiesztznr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtzppgsxjm.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtqasiesll.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwocvoet.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gthtxtbitw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtsmksxsvq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtbsoxiicm.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtazjuemda.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtmglvtkut.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtpgmqwbky.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtiseuxdto.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gthaxcmuci.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtwcaophif.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gthjntqlvy.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtoazpaqvp.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtflffuevb.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtaqwzxprc.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gthkcrglud.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtakmxopsv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gtvfwguvve.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtdbuozbpf.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtpqlkrnfs.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gtlxlyucsn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gticpgwrbb.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtgmrdcqxz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtchqxzwfv.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtlpodmffm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gtznmcvwht.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtnogosvem.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtdwjdglvf.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtknkyekgv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtmmdcpunq.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtpmlqtogg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtymqvlcct.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtdulosncl.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtcqqywwlp.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtqldremod.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtvslmhogg.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtpskdwdxz.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtqrsmwrie.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtdqjlydul.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtrctbpbax.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfoakdcnv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtoolfuzsa.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtyencedtu.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gttgsbenom.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtczbhmpys.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtyajrjcgp.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtxfxtipui.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtfenbdlli.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gtubebqmtf.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtxwddctzw.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtltfysrhu.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtswhyniyb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtwscixtok.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtzkmjbeim.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gttzhgfqqg.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtrptpivzn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtsvlpzfxs.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzctuqfu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtlxxemfrl.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gthszmbcft.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtxsdyswst.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gteijnlfof.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtmgmitikb.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gttxwmkdtd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtbdynedfa.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtjxtswktd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtihxwmbye.html


<!-- 参考信息 -->