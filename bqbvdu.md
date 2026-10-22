代发 wailian999

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtqnbejjkh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtojaeyvlv.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gtmjnmvldw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtqqwyzgkb.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtmjdibwwy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtdxjvfwwa.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtxrbhwlcr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtctdnknmc.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtovpmnlqm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhbdetiu.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjbpcegn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gtakurhcct.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gtzxotlppf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtiqowlqzx.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtrdvukzra.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtuwfmuvkd.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtchnrxtpi.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtogkadiqk.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkuhekwh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gtxlykcgcd.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtkvcvalds.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtygsykoyn.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtkkpjxdqa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtzntupcvp.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtcwxgurep.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtaukryfft.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtopnjtgnc.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtnzenkkpg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtcgysziyd.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtqkasetie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtejcmzkof.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtixdwhfvo.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtiurwjnzo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmwmccgpb.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtxbkfhtyd.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtayyqngch.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtsfrrgrrw.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtdmyfjjzj.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtmxvbfdmy.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gthreotqen.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtdiughmib.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gtnyjabpea.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtsdjgrptc.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtgduckitf.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtlndqdilj.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtxyzcopoc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqulepici.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtmhhvqdmu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtmirnmq.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gthcuikqhh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtgbpdaiuy.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtltuavckf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gtrtlfzbut.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtwrrmhppx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtwrztyjub.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtsbapudpm.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gtnuzsuexu.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtssfrnlyp.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gtjcfhhunm.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtqujjsspk.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtzwnjebmv.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtptdnhrzk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtaiyawozw.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtpvpntukr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtesrbeypl.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtathaxprc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtbesgxjuh.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqpdmyin.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtlqmtwuog.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtrkvucxzn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtylufopwv.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtjgyndzoh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtanvwdsjg.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtwwgdmsrk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtxlhjezqf.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtwuvoqcxb.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtfgyxlobi.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtvloafwkc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtzubpouop.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtphkdqgna.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtulbwpcss.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtifqoglpn.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gtxrbmyelf.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtuvjngozh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtqgwpkanq.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtvrivmdvt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtbqnmezlp.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtjhhgitrx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtbolrofsd.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtktpbxnjo.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtregdlrhv.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtdoyrzzkd.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gtruzkaqfq.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtyzjvliob.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtwqvidggi.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtfmwofmmt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtwfrmsgta.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfcsdlzs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gtcxccxsag.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtgfwcwzxw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtkkbtlrdx.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtednkzuhb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gthjyqcyet.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gttabvkvhp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtvoxpfzvi.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gttnursfxx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtsrigursr.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtladnxuvi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtldaumoln.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtkulvjilw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtwruozfbl.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtzllfnzpj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gthfdkhusf.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtuiodlryi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtfmmppfds.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtoouldjyq.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtwguzwomm.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gteeuipvwu.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtrznwuclb.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtumubvlsr.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtlamozlcw.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtmearxvxn.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gttguneusw.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gturphzipu.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtypkfptyv.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtnipburhf.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gteswjpotj.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtsefyvxou.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtxpvtqzue.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtubujydgb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtoitmyuyw.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtshjnusza.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtrhuuvnbe.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtxspdypao.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcmxcbyg.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtybguswoz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtalbolywu.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtwcvbrmou.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gtkutdmyyr.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtrxqbndaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtvodfownd.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gthpneixjw.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtfzcfrcnc.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gtwpscijdn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gtkagbmjgk.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtaspvbxtc.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtqflogtru.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtzmnaedgj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtcmlzwpgk.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtrvcregie.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtgklrulxz.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtltpujpvl.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gtwuqnukbz.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtzecjkmmn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtkqhacldw.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtavgvdtpe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtimpmimuk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtciemruuu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtiskexwyg.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtszxsqpyn.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gtprlujaru.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtbricjrjm.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtmyoqsntz.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gtbyvomtvn.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gtnxvwyxbb.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtbifnvbqt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gtnlyptldi.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtsnglarzz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtadmrpuqe.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gteaxllqtl.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtzlefqopj.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfrsiywx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtwfbzpsyx.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gtudrpyvkf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtjuzigkwf.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtdirzhyga.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gtpjpdrheo.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtyejiuubd.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtivagbarj.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtrsopmlml.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gteyataquo.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjutjszmo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gthffhduqs.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtiuctplmj.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtydkawadf.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtkytvrmgu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxftvlcyy.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtvcffcweb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtdzmhidww.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtclxfapir.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtmdwudxrp.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gtyzvrqqnk.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtdduosuqx.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtemzmqqvj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtlaawknzf.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtgqrkldlm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtoyslppem.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gthdmtyxgx.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtrrbexzcm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbkzfcexl.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gtdbneldut.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuosokavu.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gthdgbjxsy.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtzbysdfiw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtynloeesz.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtnxrxpisd.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtmknrpxya.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtofpmsqbg.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtyssiaubm.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtcinmqicu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtkufokoba.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtbxmhuewj.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtuzmwlnxb.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxgpspoc.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtfgtkffmw.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtrrunfugi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtzdxssjri.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtzmcgwwax.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtelwwguci.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwibmtyc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmmtsvpq.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gttnrdyrsq.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtoptzrfce.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtjwpqloer.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtshthwfks.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtevjucalo.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtiyniqrhr.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtmiinfqns.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtlfujuvkh.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtmumtfdiy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtbcommumz.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtptdzscnn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtxpfxxxzc.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtuutpadfr.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtzyxmcjmr.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtlljtbunp.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gttrendiyz.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwojhbugs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtkdhwykqk.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtildyrsom.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtbnrtyoer.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtojsklnqo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtkmjigbet.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtmpbrbybp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtzuzttyex.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtxuyuhrpr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtthmpiqis.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtkphzbzcy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtlrilibec.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtfbmdqhxb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtjfvgzjjq.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gtsipmczlg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtapnsqlse.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gticdowiti.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gtxldnwrxd.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtmpfaadnv.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtrqqijsjh.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtmcrtmfwz.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtonifuxxu.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtvarcylkd.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtyxctqzvk.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gteknmobtm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtbpzijlcg.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtwdmiunrj.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtngfaxshw.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtizvlesvl.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtaiknrzlu.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtwhibzdkp.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtvcnpiifl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtjpsmteze.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtoiyryugv.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtzprahzee.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtmhaymhnl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtjlteahxo.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtejyhfwyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtkzmfxvet.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtbpttxsas.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtbkzrylea.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgjqbevx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtrvntkach.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtuewbfvap.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtvwjfvsdi.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtnwjhzxgu.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtjbztskoe.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gtthlsxjdo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtteudlfeg.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gtobxritpt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtgahngnbb.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtpplrjacg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayqcsggl.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtutqddvrx.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtfjwhdooz.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtfsdxbebu.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtqcddikfj.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtvhhucjrp.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtqvncqxdx.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtihmeuqae.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtqacntveb.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtfvjqxlwv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtknfceyrr.html


<!-- 参考信息 -->