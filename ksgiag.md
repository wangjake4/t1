代发 wailian999

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2borfrriv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gt2ocfyjnts.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2zvrcmoed.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gt2hvjcwyyp.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2ijmbsybm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gt2fphvtvto.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2rxpxaoyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gt2mdpljkqp.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gt2xeieoyeg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2etdprvgg.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2czzqvime.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2drkbguno.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gt2uxkqpukf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2rhaqhrbs.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2jssxyqeb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2afmbnecs.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gt2uclrteeb.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2uylnzvug.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gt2wurvueuq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gt2csgllsok.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gt2gzeddlgx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gt2bzfikyxk.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gt2ybizlien.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gt2colkpril.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2jbtzcihr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gt2upqvvcvs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gt2mdnxdxss.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2senlvsmy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gt2oltsvlot.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2gbkyxqcv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gt2pcavkung.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2uvohyhbn.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhaajwlc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2aqqgstds.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gt2tsrbwmqx.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfzfomba.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gt2nhfsqciv.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gt2aqimlqqp.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyusojhh.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gt2kohgtoiy.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2nfdckspk.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2aotkmbua.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gt2wgbklqjl.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gt2sawntuyx.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gt2ymtwocsl.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2bffomeia.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2ryyeacuq.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gt2mzidxluo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2sekukdqn.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2askptsxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2elgldmlg.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2wkekvzkv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gt2aovwzjfv.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gt2bhqgbdgc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2cplsxhex.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gt2sqzpiwgc.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gt2xximbwek.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2wgqmkvcc.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gt2cjzprqeq.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gt2finxrneg.html

esac
来源：http://dali.shzxlz.cn/Article/details/gt2txudohte.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gt2dxhrhuef.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gt2cwkkhnnn.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gt2muvoceso.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gt2lecigzik.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gt2euoqheqo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2xlmhyouf.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2ijqxjuwg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gt2elnjupko.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbvxpyvx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2sksotnga.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gt2crmioheg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gt2aoofzrhv.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjjxhurr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gt2ljocsuyv.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkutsahk.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gt2dutvsaat.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2tfnfcgwh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2kvqyegqx.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snzrczhj.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gt2lxbxstuy.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2nyydhcan.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnugkovp.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2gvxxocja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gt2ixwepsda.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2sfpfgtcu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gt2bbhzotsv.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2xeqhqohp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2lbkdodiv.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gt2qyhbewrf.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gt2jlhrloop.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2mkzaquty.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2ovtkbfko.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gt2aezvshqt.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gt2xcpcykls.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhfsefae.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gt2wubaqtte.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gt2bfjiypvk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtcfrlsm.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2bekbdwor.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gt2zksgqczk.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gt2lzhgegdj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2crsrhgjd.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2sxbldmrk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gt2kqculqvv.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwdbrhhz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2iowhhkks.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gt2cbmixnqa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fduudbuf.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2ahpyxawq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhhawsql.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gt2aprlaurj.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gt2qtupsksh.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gt2tmxyfetp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gt2zcoatabw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2zivckxba.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2pbvdseqs.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gt2pljcoyka.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gt2jgdcxfia.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gt2yyvpqshb.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmqzqkks.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gt2rwwuigzj.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gt2rjvdrslx.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngimbcnj.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gt2hfjpbunz.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2xxrpmzdw.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gt2siormivh.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gt2qnonklyi.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyvunspi.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gt2bvndksbq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gt2aqblcfmc.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gt2ddgphchb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2zmdatcny.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gt2yuhlaeky.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2vvczdgib.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gt2sbsgwekr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gt2iockxxgb.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gt2fvdnlfcp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2rppfbhid.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfrqpnql.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gt2wvltdpak.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gt2culdxrsh.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2vhjuunmy.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gt2hdybqxcn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gt2qzcgjomn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpofbmvb.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2ystpohzn.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaifhdjb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gt2ufyztfpc.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2tduiymae.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2onnkinme.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gt2pehymrzi.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gt2uilemxpy.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gt2jexglcqo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2qvvnovsg.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2mbzhehqh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eimdawoc.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2vonbkdxf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gt2pyxhxpgx.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gt2jsfxpabl.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gt2ecudvmay.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gt2ffeytwhk.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2trbhxiyl.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gt2zuudakkr.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gt2lzkmwvaw.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqauwyqw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uaaezgwu.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntsszgyy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gt2wiwffhtp.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2nbbsqqxf.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2vctjhimj.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gt2dblybjqv.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gt2mzfnnfdz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntojfahu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlecpokr.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gt2kjbzuayi.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gt2rmuxhfwq.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gt2wqmrfhbg.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2zjjcrwzz.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwagxrji.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gt2sqcxhjiu.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gt2bbgvypnj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2wdviwlbk.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gt2vnscaboc.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2qgugdkif.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkztmxbh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2pnivfxdp.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njuiwukt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljhqzuer.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gt2szcstjun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2izhlkeew.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gt2cbehapsz.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gt2uxayxlpy.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gt2arhwpokv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gt2vguhhhpo.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gt2fleuhybp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gt2jxvabirm.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gt2fkxggcqq.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gt2jzwaanah.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqvlytrn.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gt2itukpesy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vemmjcrs.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2fenwcyzw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2toptxvvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gt2ymewdqrb.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpwflprx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2oiwfqhmu.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2ntrrqjlh.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gt2gxylyexo.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2skielpka.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gt2djleuccc.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2makmzxuz.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gt2chjrvptp.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2aivcnjqq.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2texhtoqc.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2cchzdzja.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gt2lodnvjkl.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkmrqyyy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gt2ucmoruix.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gt2pxlhaict.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gt2nmascolp.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gt2pwxrjjyc.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zphiyhhp.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2mzsfhnou.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gt2hfwmggrz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2cuuxakbq.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gt2mkoinydb.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2hngnobcb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2kktpfjhj.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gt2zykrkrmu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2akbrmtje.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gt2ismpjfww.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gt2dhnwreoj.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwaupkpc.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gt2xiuhkgao.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkpitsgr.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gt2aosxczoh.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2lcotijyi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gt2qokorojq.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzalrcfi.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmdtahgz.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzjoqnjk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2hydfuzxw.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2lasmvgti.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2kdkznhex.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2nztiynqt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2equymawb.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gt2ijynnngy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gt2wxudfzrc.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gt2xwjihcwi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2jchkcfak.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gt2swajdpsz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gt2byhclxdb.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gt2mhhqvmci.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gt2zentoolr.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gt2eebryjlm.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2qgdzsarj.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gt2czkhthep.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2gnkrxvhr.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gt2rcnxyhds.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2ymlzcnee.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gt2jiktepac.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gt2shsxfcgj.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqqljfvn.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2glycfnnv.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gt2emgpfjhq.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gt2qxhesrmd.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2hjirmizh.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2bdstutpo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vffrgcne.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gt2quszpuyf.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gt2uojvvaaa.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gt2ebrlnzmh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2bslkpcmi.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gt2uruwumkn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hqgvnfmf.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2oiosnixv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2czwbjcrk.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2mvpojdux.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2jgpjfawh.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gt2linofpal.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2zxcsndqn.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2cvaqbhsp.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2dbigkrvb.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gt2rgwwdiys.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2unguioos.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnyuyafh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gt2vehojwjp.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2ndryjbgq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gt2aezskyei.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiczpcdg.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gt2hkfxnhnb.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gt2oifuooqr.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzjxynvx.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2lbzjrahq.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2qstlhhfn.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2ibewqnfu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2mlftisor.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gt2wxwtajls.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2hzolyldo.html


<!-- 参考信息 -->