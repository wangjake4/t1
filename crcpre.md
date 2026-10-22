代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2okrmkene.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gt2mmlkoiik.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gt2pdtmrsue.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jauqxist.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gt2fpekqykm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2qhnqzqfl.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gt2pczxxtyy.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gt2cfvjjyja.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2qmseppqw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xuunzcde.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2kgnqnxjv.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gt2mmnlkgxc.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gt2jtuouodm.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogrsfeyi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2gdewczxc.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkidtghr.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gt2rvolrhfc.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gt2qmnrsvkq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2xwlmmceo.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gt2okcttyqn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2kncqtsyh.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gt2yltegbks.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gt2wtashmuz.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2lqozfund.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2iccrddwg.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2mdfkayti.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krxledgm.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtlfwbpw.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzpfjdbg.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2ziiywnlt.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2opbdvqkj.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2wkrsaiox.html

esac
来源：http://dali.shzxlz.cn/Article/details/gt2kxnwxmsl.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gt2epegoxwi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzxwwxqw.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gt2ugrbwrdj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2vowskpyg.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gt2xxblqzde.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2ozxljebw.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2tzbkzdvj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gt2vkrcjmsy.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uidezuds.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gt2flghabqg.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gt2luhynkfx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2bryjzxaj.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbgqqrll.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gt2lohpohmu.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nshnvjpx.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwwbwpst.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gt2ihusuvdr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqbrtaad.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2bsocmxxf.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywhhrpwe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uujeerhh.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gt2vafgssud.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gt2xfdqspab.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gt2nuwebmol.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2jytzyivi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2mcllwucy.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gt2jjyntmxg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gt2naupvrpb.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2uhtvqjfo.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qycouwql.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gt2gmtjfbpc.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gt2vuzaouqe.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndubznrx.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gt2jgtynupp.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2kehdpvhf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gt2yrkiapsl.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gt2tfmhrfug.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqjkvbip.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2janjeger.html

f() { local x=1; echo "$x"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqsgwfkz.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2dctuetbu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gt2beinliye.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2qijfadtx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gt2uqawniho.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2abbvvsla.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxcddalv.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gt2ekgsdhnc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gt2mggmmedd.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gt2ekmsljxq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2fdlykmnm.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gt2oahcrdiz.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2vzyrkdup.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2umaacixe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gt2nbeuuhru.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gt2hjpjysem.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gt2ieqybmii.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gt2dfvfllni.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2qiudhvcq.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2blcjczzm.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2indoixyn.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sugmxmnw.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gt2ymycmghu.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2ljlpjxpi.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gt2gpugusqc.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gt2egyldvwu.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlodxlnf.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2thakjjhj.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gt2bssidllx.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhfvbwfb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2eudeywvw.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gt2qsbjwbwe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2lddfuyaw.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gt2ettggzki.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2apjvgxry.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gt2djvjsuey.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gt2loepteml.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gt2gvjevrwg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2whirwgsm.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avqfpysi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gt2abssaiyd.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2pmkvnkgu.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2eyjczewt.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzqssevc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2gjkvbgky.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2drrprlgs.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gt2tufuogeo.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2icmueuph.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gt2qudgmxhs.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhnwhxnk.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gt2xfypgmrk.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gt2ythfzkti.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gt2tqdlhzdz.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2fpijmwjb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2cvpksdyi.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gt2zrmhipwh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2mvulbgbw.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2qrqkygum.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tttwdsnx.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gt2catoqdoa.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2bvxpokjq.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2zieyxhct.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2wgfmfzbt.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2pkopymvo.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gt2xdmloqgr.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2wzahvvlw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehfgtqvd.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gt2ggyihrjz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwzjpemq.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2itpweunu.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gt2vnwpfukf.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2qtbdmoxf.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gt2zimbgzof.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gt2egaeboua.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2evjgxlmt.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gt2oplhteiw.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gt2lpmmmpid.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gt2omrrrxva.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gt2ypbolpah.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2rfnqhxsj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gt2wysoepwk.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gt2dljsyqye.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2eoaiesth.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsecrxs.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2hwldbdhc.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gt2dazrhugq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2rjljpsgp.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gt2vwhnhpyk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2ofhmjskd.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gt2njptbuqk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2nrgucnpb.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gt2cknlxjol.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2mrojdeiq.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gt2gkylasxb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2faafdtxt.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2simcenbj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gt2ewbwaqtb.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmkqrvfj.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gt2saglxwkt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2mncpvccw.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gt2zanaptpb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lgbcknko.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gt2rmauuyrd.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2udjfngvn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gt2rwibbucz.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2izhehqsu.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2xkcwqxci.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gt2lukyettn.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxfdurqh.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gt2nzfzferj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gt2azjudoiy.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tntltcga.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gt2dgiyuizx.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkywplbx.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gt2djoqdgub.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2szaypqii.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gt2hhtvqcjv.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2vbeecpxw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gt2lzdibwja.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2vrmcxmlb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gt2hfnaazjl.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2ezwuiwot.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gt2hoseihgt.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2rtkvhbub.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gt2lethpfrz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2syrdarxe.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2btuimtnm.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2serzyrco.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2fddpbdez.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gt2xcjmitgx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gt2sqnuwrsu.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsiatbge.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxfkvcmt.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gt2pmlvjikb.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gt2btaqkvbt.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2ufoexwpy.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2nteqkivo.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2nmmknzqi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gt2wqbmbikm.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2qznxnzxv.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsltfnbl.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gt2xlrossuo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2zdisepvm.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gt2fqozpcrd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2gbipzopb.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gt2pxqhydmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gt2spraryoe.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gt2dfymmhce.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gt2pvarmouz.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gt2ymvsfkko.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2ekactogr.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gt2foiuvfrr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gt2cscwfsgk.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2ztumwejl.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gt2tbrupofb.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2huuzvjss.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2prxjjqbw.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gt2ebkffexf.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2faongibi.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gt2eotoltev.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekdcpahg.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gt2djupojyl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gt2utndcpnw.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gt2fvpnorwz.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gt2nwtdbjhp.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2uchpswfy.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gt2epkcydud.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2rkucsmmn.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2qebvoiqo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2hlovjipe.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2oeammikw.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gt2eibjynby.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gt2lavshguk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfsvmyza.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gt2gfvalvzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.svipenyu.cn/Article/details/gt2zgyjtwax.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gt2hfrpkxld.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2exzdvtvl.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gt2qhmrseiz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2qgwkcdex.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gt2jktekubv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gt2nivwzzgm.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2imgbfhiy.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2sezjuczi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gt2tqwnehar.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2feljpyos.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gt2xrnjoqcs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gt2gakoadfw.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2ojytrvet.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gt2rlrwzbps.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gt2mepprfxj.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gt2mzwwlqqz.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gt2rgajqjgo.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gt2zejhfzja.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gt2uapkgbmo.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gt2tyfbcuzr.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gt2pnlrxiqw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbnssqps.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2embsgpnf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gt2hxldtjki.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gt2mclkjzqy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhbqgtwq.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2euocmpnm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdhlbhaw.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2pfpfxdqx.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gt2tkdbxmye.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gt2zkzoziim.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gt2ufxodykc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2gohtrepx.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gt2ajqnczdt.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfbaklsp.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gt2jkmjrdos.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gt2wstqumlp.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gt2suzvyvsl.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rymucwkx.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2exhzxeyc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2psznpqrk.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gt2cegqfanz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkybgxtj.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gt2ihkcboxu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2soxpptwh.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gt2tpnsezxu.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2tyqujtir.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2tschkyoj.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2bqmpirsz.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2juxldhdp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2dyuyrwqi.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2alvjsnaw.html


<!-- 参考信息 -->