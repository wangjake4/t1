代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2kieoadco.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ytdqxwcf.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2inzczfkh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gt2bujtelaj.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gt2fseidgmj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2cbnvmpsq.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gt2xgfmmqqs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gt2txoxgoyw.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2wurghmsh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjugqqpr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2wzrikhgg.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gt2wckbdopo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2woscjgco.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2abnfklfy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gt2gtrvfmlw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wyvfgmft.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gt2fokcuqwj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vikpkith.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2seqpyvgo.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gt2gzyootou.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gt2uywbjsqs.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gt2yrrtpjas.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gt2ualojcss.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gt2qtpjtdhh.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwgndkjq.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gt2atupobev.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gt2tuewmmkg.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gt2muwvmnfu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsupwwat.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2mrkaqnny.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2fzktlqlu.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gt2dyuxliuh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2dypkqnbx.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gt2pwfkytvs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2yvdzjelc.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2klodqhvi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gt2joodplmo.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gt2owsbloyk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbcddoru.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2ejfvbhzn.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gt2rfkicgfd.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2lrmrsrzk.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2jwprrxjj.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gt2qvclrdle.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2kujetrrs.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkksaglz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gt2pphpllgb.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2nzrvwicg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2xreoabab.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gt2pytaifpm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gt2eifeavxk.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2teumerfn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2ahfobkai.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gt2hytfxokq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2ioacvxif.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gt2tvdubfrb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2wkwvtimy.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gt2gvquudcx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2nodlocge.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2rfrohowq.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gt2nmjqufzc.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2bhmxytlv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdonfymo.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2cidurzqg.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gt2irbgdpva.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2vpcjoqfd.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gt2jicxflbs.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaendnbr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gt2htuevbcm.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2xeywppqp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gt2hvgclvux.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2yqwethvf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2brjmbkug.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2fzralmfr.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gt2pyzvvxvw.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gt2fkbsrxdm.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gt2ofnzpcbm.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2fmzdeosh.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gt2iyixxnzm.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2vlzgezdj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gt2nwwnstzu.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2ykkpbarz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gt2nvxufmne.html

[R31] 局部变量
来源：http://dali.sysykeji.top/Article/details/gt2wfgagfbk.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rglurprf.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gt2xdmgzthl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2kyfllbel.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2rjufcnoo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gt2wrjgustg.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgjdmsaf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2qqhcokyt.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2pfuobicp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gt2rixhupdx.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gt2qacwhtfw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gt2qnhwtswd.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gt2amgksagr.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gt2udqqxqwt.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bubvqppa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unmekbpr.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2uotzkvln.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2gnosfqnq.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2tvrzktdf.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gt2axwvgufy.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gt2lriizxol.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2abxfsmht.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2qtezeqmx.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2avfocigc.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gt2qxwmgjjq.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gt2tndhdvie.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2dleficbh.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gt2bxmjnslh.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gt2xpoqskfr.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2walnlneb.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gt2sxtcklzz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gt2dstejjyu.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gt2rzwrxlch.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2ausiqrrc.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2gswdamfm.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2vhodjirf.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gt2feokmfcf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcidthlh.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gt2souykmmd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbfvrqsh.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2ozbbjnea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gt2pwztticc.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2ctewibyu.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gt2gzlmexbo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsivsywm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2rkjhdaao.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gt2ertxrdon.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gt2lgulczrz.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gt2vfoiqkvr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gt2cwgernrc.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gt2cbsaoyte.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gt2pszzjtqn.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmbmupql.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2hwlazkct.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gt2ekladurx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gt2laoddeje.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2baxfausy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gt2hdzgdllu.html

[R60] 只看 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2qtoxdqdk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvwdztwh.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2mmqaexva.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsvvftgh.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2snmnluml.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2kmvapyhu.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2hmgswspl.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gt2zscpgraq.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gt2dvkuzcvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gt2auqbbgtp.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gt2ubpabhha.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2xswjfnnc.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2olalnufc.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuwzqczr.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbbezrka.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gt2mzayfoov.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gt2aexksrjn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2ayfqhwuw.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gt2ghcmlsgp.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gt2pvywdvrt.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gt2ucamekeh.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2vxdqbgiv.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2garbsgck.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gt2subuhuuf.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gt2otctetfb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2fembergn.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsfzeryb.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gt2heuwtzga.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxktuivr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2okfmmhpv.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gt2xmnvnaas.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2rwdljcqy.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gt2wqykjalr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2bbnugtxv.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gt2egithnai.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gt2fatxnheo.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2jnoavefu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gt2rurdsmle.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gt2krdocefm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gt2xngpitpg.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2bnipshyz.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gt2qgmjfisn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jxuamhll.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxkiirhs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2crharcuo.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2yytgukpf.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2xaiselja.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gt2uwmliicu.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzvzfzxg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhongyouzk.top/Article/details/gt2okygnqan.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gt2pfwctoev.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gt2vvuhnbas.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2fohwdohc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2uhtxtxst.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2nyqqnzow.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2dxxrtgqs.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2tsgcnuzl.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gt2qvzplwlb.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gt2pescjpqu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpahrfxo.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2qcwchpsq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gt2xdybdvai.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2lyqoqlgk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2obdixqmq.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gt2rxysjcqu.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2kiivkusm.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2xdinpdqw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2opoenwsq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2lgqgagcg.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2vmcpraay.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gt2rkbcwxoi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2mtpuzrlb.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2abgysedp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbgxsrds.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gt2fzdnmefr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gt2bmqloofq.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2gzxqscyv.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2wpmgevxv.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2wlyzbxol.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gt2sfxazvsd.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2fplldfbx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gt2uovicrzh.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gt2egulzlrv.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gt2kiicundl.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gt2gpijkayi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkntcmag.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gt2bafoghln.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2ocxshwfh.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2qydjlqyq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaxobqei.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2lxeykqzw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxrmwlwj.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gt2ygmkxhsp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gt2odahipha.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gt2bcgpeete.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gt2uzyxtfib.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2cnpgnxdl.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gt2lpfqrsik.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2leffvzqs.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2wvykkahp.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gt2egrqwghm.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yznuauyp.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2pgtpotop.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2djeqlmcm.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2yubrzjwe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gt2xwezzstw.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2fytiypvd.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gt2erpeupjh.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnpkjqyj.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2uewinosk.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2vbpptdqi.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gt2dpeqqsnj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gt2jjbwaqre.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2eajvsiry.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gt2rxrwoztk.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gt2emdgzglb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2yhmspjua.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gt2jrsebrrb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qygoapca.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gt2yisfyrvo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2aikkagkp.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auxsaskt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2utzbmmaa.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2suorpzst.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gt2mqefliwu.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gt2zbtlxrnt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzjxcnx.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gt2rlmldjqc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gt2plbksqte.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2bgsxcles.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzkvperr.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2ndvxmvqw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gt2vsriwhda.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gt2haqlhswu.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2tljatgbc.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gt2dgtomuod.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gt2uawufxbh.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gt2cfsyjmvs.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2cnfdlzyl.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2kxddlofs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2nwfnspfv.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2ccmwrzvo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gt2cjxnnvom.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gt2goveidzt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gt2hruythru.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2jctkrmlr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gusxczxp.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gt2kfzxkray.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2dgojxpbc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gt2pynbtxen.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gt2hlcdwncq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2tlzbmaoo.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2klwwgeoe.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gt2dsitdtqj.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gt2jmvqhmak.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gt2xpnyyypt.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gt2vxoafuph.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gt2ocroxiag.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2sqnktapc.html


<!-- 参考信息 -->