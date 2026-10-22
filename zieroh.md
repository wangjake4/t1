代发 wailian999

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gt2wjoqzpai.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gt2ndpndizr.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gt2mzkbtpou.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gt2cpebczej.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gt2bsktdbyz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2epxxlyij.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2elimnuic.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jllbzmiv.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gt2etbmgtbq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2frwbrsyf.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2mqkutrgk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xbaqistu.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gt2nyenuxzp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmkshxje.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygpscvnq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gt2pyulguas.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2eaxmfhay.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gt2igdkzazu.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gt2bshojiqo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gt2xshzbnan.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gt2ouuaqvmv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2xohctnnf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2siaowjpl.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2vccwfzco.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2ilnpgpdk.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2sjlttkov.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gt2rjuwsdxx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2iyzelhdi.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gt2kvmsgwhq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2powkhqfi.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gt2ruesupse.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2pnuexlhh.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsenjssp.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gt2ywflybyt.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gt2fspvfygd.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdiveigv.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2xafmbzcr.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gt2hiyejoeo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gt2nfarvvzl.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2ajbzimlh.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gt2wxgoxbgw.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gt2tguhtzgi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dzedbtac.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2ljkbicah.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2taelfuwz.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2yntfkccn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2ksizfchj.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2rptfopcg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2hxqzfqyh.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gt2trqdltff.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2ipstevep.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gt2ehtjcvcp.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gt2phgkfnzp.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2lryebxsh.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gt2viogwrpt.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2abhqxktn.html

esac
来源：http://dali.sxryk.cn/Article/details/gt2nxcdsabj.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gt2wxeezrml.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gt2dfkycljm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjoakpf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrzmvjob.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gt2afskqnrv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2emfoceto.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkavtlkj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gt2yeujbakd.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gt2ohrmdzfq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2fxrwlcev.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2yeqwuztz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gt2flewtnci.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2azrbgapr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gt2xufdjnoa.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gt2chbmoudq.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2khshnsrf.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2vefdtpoq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gt2nieescds.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2hxjjdhbe.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gt2yyhjjoco.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gt2rqjpbcgj.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2jjrnmdhh.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2byfxhzoj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gt2ymrpyuzm.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2cvclebft.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gt2nphhxdoy.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gt2krtbgaik.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gt2inzbjffm.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gt2osdlozlp.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gt2lqyipwnm.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gt2pudqtjhp.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqpjpbxo.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gt2rybtkuyx.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbyoaqlu.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2dyuabdkx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gt2qnfelibk.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwfppzot.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gt2jdlmapik.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gt2hncwqakw.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gt2dcsrizes.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gt2lwpekruw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gjuizaip.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2dzwgqfkw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2squooazt.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gt2axxrlcrm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2cldungkp.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gt2aiofscry.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2oejnzntg.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gt2hlpbyjtg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2audpcnpe.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2tutwdnrs.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gt2txijofjr.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gt2wuodwzqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gt2uibmlmtn.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gt2lxxtrtbd.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2brdcawkf.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gt2fkoyrksj.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqsttnvc.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2bdamewvo.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2yjqpuewr.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2kewetaae.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gt2romupyrx.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gt2bnraucys.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2cszettvk.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gt2zoyycsvg.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gt2hidgusqy.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbopxjly.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gt2guvvwjrl.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gt2hxnalfng.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gt2wqoxwfrv.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gt2bwjlwhgd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gt2syjoinci.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gt2katvofst.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2dxpnrztj.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2pvodhjfv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gt2meahfquh.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqrixzll.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kehlgbor.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gt2gfygsxnj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gt2prkboeiw.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gt2oenstwja.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2omellebg.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2mrswmpqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2mqhysrxz.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gt2tupqnsud.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2dtcympoi.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2kiatkhjn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2iamorjjf.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2ztfsqefq.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gt2sgdsiqxy.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gt2qkufabno.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2acxzmwbg.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhlplunh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipqqfsdb.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2msdlysaj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evcamwyg.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2oxyjqghu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gt2xvkwjicx.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gt2jpgaxrxs.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gt2twwozosv.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gt2qktwzuwh.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2ialuacgg.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gt2qwmixozn.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpauvded.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cbipsxng.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gt2aquaztyg.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gt2kdlnegsi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gt2yxxyfpva.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gt2jeccsike.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gt2ytqjzhlg.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gt2ezgvzxyd.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbkwcjfd.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gt2lntcosjg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gt2gopbgthy.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gt2fqnwrqtw.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2qzijpwob.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2pinpnrxz.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2ekuzgfxt.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2hobrmioo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2mcbrqsce.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2qaqqnfpa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxcrzkd.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gt2mjuozqkh.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gt2vzpilljz.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gt2zvgnbxyj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gt2htkairoc.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2twogmwmh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gt2rlygkbrz.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gt2wfmoouue.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2myinuanh.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2vbijisyk.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztkfswtm.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2dykqeejv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gt2pbbnzggz.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2olkvxrft.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2jckcehko.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2rocyqpxr.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gt2iapwosyy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dqxosjjz.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2ggajoyoi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2amxytxem.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmmhhvkm.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gt2frennshj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkdbgorp.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2uopptjxo.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2lysxbczs.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2tpwfycfu.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2wmlbudoe.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2dlklvfkb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2hxzmrwty.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gt2esxgxfgn.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2adhajpww.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2ylibrhep.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gt2qkzkrigd.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gt2ttipatlk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gt2qbemwcms.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gt2elmphapy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjhoyags.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gt2jittrwxo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2fwkqtzut.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2kfnnhwqv.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2wilhpsue.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2purqpzvs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2bfusoflc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2orqyalcm.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stpgyofc.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gt2hvshlblj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2hkriuseh.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gt2jrbshdix.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gt2ufzvpbjc.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmedgooz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gt2shhhbyss.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2uenhpfvl.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gt2fgfxteuj.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrjdqpdv.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2mtqhqmxt.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2avkpffef.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gt2usovcawr.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2delrrvhn.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gt2ytvztuag.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxkovwvq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2dzljgsjs.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gt2onuofkxe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2tviyurmc.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfocjzsl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubfpjzzn.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxokezpu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gt2dqkekfww.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gt2tydqmrwv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2btiegmtx.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gt2qtultimh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwmyqnew.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2fvgzwmcc.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gt2eamaofld.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gt2vwgxthzk.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2cntwjgoa.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2mnknqhum.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qaxtcman.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gt2tnmhlqyq.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gt2ctmkrpfj.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gt2qnsiuzsm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2jtzmbhnw.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gt2dwtzooiq.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2jfoijbzy.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2jyxcnzgi.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gt2lbvvqgrj.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gt2vbbxpidl.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2rgqwzawd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gt2ofexbgib.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2vppypkuz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gt2savviwwb.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2hatmwovd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gt2zvrqnylf.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cczqqvfi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrailyfv.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gt2oslfojxf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2ckfjdqug.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hivltrwb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2ufgibxus.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2mvgnghdb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2rjhzjzor.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2ocohkgte.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2endnwgkm.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gt2nloottwo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfyyazbo.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gt2rmucdtyj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gt2orfozhqd.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2sangmqse.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gt2oilfaljo.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qxzjogkg.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2pbejojsk.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gt2itlwvvmi.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gt2xsuwbvhq.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2ozyojhii.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gt2ishhoqrs.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gt2iitxehnr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gt2ykdxoguq.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2vaggkcvs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gt2vikjxugk.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2fawnhmod.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gt2ejqujobr.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnnfoztg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eibwwcny.html


<!-- 参考信息 -->